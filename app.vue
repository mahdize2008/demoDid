<template>
  <NuxtLayout>
    <NuxtPage />
  </NuxtLayout>

</template>

<script setup>
onMounted(()=>{
  $('.accordion-item-header').on('click', function () {
    if (!$(this).parent().hasClass('active')) {
      $('.accordion-item.active .accordion-item-body').slideUp()
      $('.accordion-item.active .accordion-item-header .accordion-item-icon').toggleClass('block hidden')
      $('.accordion-item.active').removeClass('active')
    }
    $(this).parent().find('.accordion-item-body').slideToggle()
    $(this).parent().toggleClass('active')
    $(this).find('.accordion-item-icon').toggleClass('block hidden')
  })

  $('.menu-button').on('click',function(){
      $('.menu').animate({right:0})
      $('.backdrop').fadeIn()
  })
  $('.backdrop,.menu-close-button').on('click',function(){
      $('.menu').animate({right:-320})
      $('.backdrop').fadeOut()
  })
})
</script>