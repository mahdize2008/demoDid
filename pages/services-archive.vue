<template>
    <PublicLocation name='خدمات' link='/services-archive' />


    <About :title="about.title" :subtitle="about.subtitle" :text="about.text" :videoTitle="about.videoTitle"
        :btnTitle="about.btnTitle" :videoSRC="about.videoSRC" />

    <About :title="about.title" :subtitle="about.subtitle" :text="about.text" :videoTitle="about.videoTitle"
        :btnTitle="about.btnTitle" :videoSRC="about.videoSRC" ltr="true"/>

    <ContactUs />

    <About :title="about.title" :subtitle="about.subtitle" :text="about.text" :videoTitle="about.videoTitle"
        :btnTitle="about.btnTitle" :videoSRC="about.videoSRC" />

    <About :title="about.title" :subtitle="about.subtitle" :text="about.text" :videoTitle="about.videoTitle"
        :btnTitle="about.btnTitle" :videoSRC="about.videoSRC" ltr="true"/>

</template>

<script>
export default {
    data() {
        return {
            about: {
                title: "طراحی کمپین دیجیتال",
                subtitle: "با یک تیم حرفه ای بیشتر دیده شوید",
                text: "لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان گرافیک است. چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که لازم است و برای شرایط فعلی تکنولوژی مورد نیاز و کاربردهای متنوع با هدف بهبود ابزارهای کاربردی می باشد. کتابهای زیادی در شصت و سه درصد گذشته، حال و آینده شناخت فراوان جامعه و متخصصان را می طلبد تا با نرم افزارها شناخت بیشتری را برای طراحان رایانه ای علی الخصوص طراحان خلاقی و فرهنگ پیشرو در زبان فارسی ایجاد کرد. در این صورت می توان امید داشت که تمام و دشواری موجود در ارائه راهکارها و شرایط سخت تایپ به پایان رسد وزمان مورد نیاز شامل حروفچینی دستاوردهای اصلی و جوابگوی سوالات پیوسته اهل دنیای موجود طراحی اساسا مورد استفاده قرار گیرد.",
                btnTitle: "مشاهده جزئیات",
                videoSRC: '~/assets/img/picture-17.png'
            }
        }
    }
}
</script>