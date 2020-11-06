<template>
   <footer class="footer">
       <div class="down_rectangle_webf">
           <p>Разработка и продвижение сайта - Digital агентство «Веб Фокус»</p>
       </div>

        <div class="footer_icons">
            <h5 class="h5_footer">ООО “МК-ПРАВОВЫЕ ТЕХНОЛОГИИ”</h5>
            <p>УНП</p>
            <p>192710862</p>
            <p>Наш рейтинг</p>
            <p>5 из 5 (15 отзывов)</p>
            <div class="social_icons">
                <a href=""><img src="../assets/footer/vk.png" alt="icon" ></a>
                <a href=""><img src="../assets/footer/odnoklassniki.png" alt="icon" ></a>
                <a href=""><img src="../assets/footer/linkedin.png" alt="icon" ></a>
                <a href=""><img src="../assets/footer/instagram.png" alt="icon" ></a>
                <a href=""><img src="../assets/footer/youtube.png" alt="icon" ></a>
                <a href=""><img src="../assets/footer/facebook.png" alt="icon" ></a>
            </div>
            <span class="text_site_map"><a  href="#">КАРТА САЙТА</a></span>
            <img class="fotter_up_arrow"  src="../assets/footer/footer-arrow.png" alt="footer arrow">

            <span class="footer_privacy_pol"><a  href="#">Политика конфиденциальности</a></span>
            <img class="foot_down_ar" src="../assets/footer/footer-arrow.png" alt="footer arrow">
        </div>

        <div class="footer_ofices">
            <span class="footer_our_ofices_text">Наши офисы</span>
            <hr>
            <div class="footer_all_addresses">
                <div>
                    <span class="adress_head">Отдел в Могилеве</span>
                    <p >Адрес</p>
                    <p >г. Могилев, ул. Космонавтов, д. 19, оф. 507</p>
                    <p >mogilev@jurisprudent.by</p>
                </div>
                <div>
                    <span>Отдел в Гродно</span>
                    <p>Адрес</p>
                    <p>г. Гродно, ул. Карла Маркса, д. 31-1, оф. 1010</p>
                    <p>grodno@jurisprudent.by</p>
                </div>
                <div>
                    <span>Отдел в Бресте</span>
                    <p>Адрес</p>
                    <p>г. Брест, б-р Шевченко, д. 4,оф. 401</p>
                    <p>brest@jurisprudent.by</p>
                </div>
                <div>
                    <span>Отдел в Гомеле</span>
                    <p>Адрес</p>
                    <p>г. Гомель, пр. Ленина, д. 10, оф. 901</p>
                    <p>gomel@jurisprudent.by</p>
                </div>
                <div>
                    <span>Отдел в Витебске</span>
                    <p>Адрес</p>
                    <p>г. Витебск, ул.Гоголя, д. 14, оф. 614</p>
                    <p>vitebsk@jurisprudent.by</p>
                </div>
            </div>

            <p class="footer_minsk_cont">Контакты в Минске</p>
            <div class="footer_ph_numbers_only">
                +375 (44) 755-01-01
                +375 (29) 550-01-01
                +375 (17) 374-40-60
            </div>
            <p class="footer_adress_only"><b>Адрес</b></p>
            <p class="adres_webf">г. Минск, ул. Широкая, д. 3, пом. 146, оф. 4</p>
            <p class="rf_rezident_only"><b>Tелефон для связи резидентов Российской Федерации</b></p>
            <p class="whatsapp_foot">whatsapp +7 (989) 166 24 00</p>
            <p class="down_email_urispr">info@jurisprudent.by</p>
        </div>

        <div class="footer_opening_hours">
            <span>Время работы</span>
            <hr>
            <p>Прием посетителей</p>
            <p>Ежедневно с 8.00 до 19.00 Выходной: суббота - воскресенье.</p>
            <p>Прием звонков</p>
            <p>Ежедневно с 8.00 до 22.00 Без выходных</p>
            <p>Онлайн консультант</p>
            <p>Круглосуточно 24/7 Без выходных</p>
        </div>

   </footer>
</template>

<script>
export default {
    name: 'Footer',
    props:{

    },
}
</script>

<style scoped>
    .footer{
        position: absolute;
        left: 0px;
        top: 9130px;
        width: 1920px;
        height: 705px;
        border-top: 1px solid rgba(0, 0, 0, 0.1);
    }
    .down_rectangle_webf{        
        position: absolute;
        left: 0px;
        right: 0px;
        top: 650px;
        height: 55px;
        background: rgba(0, 0, 0, 0.1);
    }
    .down_rectangle_webf p{
        position: absolute;
        left: 773px;
        right: 773px;
        top: 17px;
        height: 20px;
        font-family: Lato;
        font-style: normal;
        font-weight: 300;
        font-size: 12px;
        line-height: 20px;
        letter-spacing: 0.02em;
        color: rgba(0, 0, 0, 0.8);
    }
    .footer_icons{
        position: absolute;
        width: 270px;
        height: 410px;
        left: 375px;
        top: 50px;
    }
    .footer_icons h5{
        position: absolute;
        left: 0px;
        top: 0px;
        width: 270px;
        height: 60px;
        font-family: Commissioner;
        font-style: normal;
        font-weight: normal;
        font-size: 20px;
        line-height: 30px;
        color: rgba(0, 0, 0, 0.9);
    }
    .footer_icons p:nth-of-type(1){
        position: absolute;
        left: 0px;
        top: 130px;
        width: 29px;
        height: 20px;
        font-family: Commissioner;
        font-style: normal;
        font-weight: 500;
        font-size: 13px;
        line-height: 20px;
        letter-spacing: 0.01em;
        color: rgba(0, 0, 0, 0.5);
    }
    .footer_icons p:nth-of-type(2){
        position: absolute;
        left: 44px;
        top: 130px;
        width: 68px;
        height: 20px;
        font-family: Lato;
        font-style: normal;
        font-weight: 300;
        font-size: 13px;
        line-height: 20px;
        color: rgba(0, 0, 0, 0.5);
    }
    .footer_icons p:nth-of-type(3){
        position: absolute;
        left: 0px;
        top: 160px;
        width: 80px;
        height: 20px;
        font-family: Commissioner;
        font-style: normal;
        font-weight: 500;
        font-size: 13px;
        line-height: 20px;
        letter-spacing: 0.01em;
        color: rgba(0, 0, 0, 0.5)
    }
    .footer_icons p:nth-of-type(4){
        position: absolute;
        left: 95px;
        top: 160px;
        width: 112px;
        height: 20px;
        font-family: Lato;
        font-style: normal;
        font-weight: 300;
        font-size: 13px;
        line-height: 20px;
        color: rgba(0, 0, 0, 0.5);
    }
    .social_icons{
        position: absolute;
        left: 0px;
        right: 0px;
        top: 241.5px;
        height: 27px;
        display: flex;
        justify-content: space-between;
    }
    .social_icons img{
        width: 26.5px;
        height: 26.5px;
    }
    .text_site_map {
        position: absolute;
        top: 320px;
        font-family: Lato;
        font-style: normal;
        font-weight: 600;
        font-size: 12px;
        line-height: 20px;
        letter-spacing: 0.02em;
        text-transform: uppercase;
    }
    .text_site_map a{
        color: rgba(0, 0, 0, 0.75);
        text-decoration: none;
    }
    .footer_privacy_pol{
        position: absolute;
        left: 0px;
        top: 370px;
        width: 162px;
        height: 40px;
        font-family: Lato;
        font-style: normal;
        font-weight: 600;
        font-size: 12px;
        line-height: 20px;
        letter-spacing: 0.02em;
        text-transform: uppercase;
    }
    .footer_privacy_pol a{
        color: rgba(0, 0, 0, 0.75);
        text-decoration: none;
    }
    .fotter_up_arrow{
        position: absolute;
        left: 99px;
        top: 324.18px;
    }
    .foot_down_ar{
        position: absolute;
        left: 177px;
        top: 384.18px;
    }
    /* ofices */
    .footer_ofices{
        position: absolute;
        width: 670px;
        height: 505px;
        left: 675px;
        top: 85px;
    }
    .footer_our_ofices_text{
        position: absolute;
        width: 112px;
        height: 25px;
        font-family: Lato;
        font-style: normal;
        font-weight: normal;
        font-size: 15px;
        line-height: 25px;
        text-transform: uppercase;
        color: rgba(0, 0, 0, 0.5);
    }
    .footer_all_addresses{
        position: absolute;
        left: 235px;
        top: 60px;
        width: 435px;
        height: 25px;
        display: grid;
        grid-template-rows: 1fr 1fr ;
        grid-template-columns: 1fr 1fr;
        grid-gap: 35px; 
    }
    .footer_all_addresses div{
        position: relative;
        width: 200px;
        height: 125px;
    }
    .footer_all_addresses div span{
        position: absolute;
        font-family: Commissioner;
        font-style: normal;
        font-weight: normal;
        font-size: 14px;
        line-height: 25px;
        letter-spacing: 0.04em;
        text-transform: uppercase;
        color: rgba(0, 0, 0, 0.75);
    }
    .footer_all_addresses div p:nth-of-type(1){
        position: absolute;
        top: 35px;
        width: 200px;
        height: 20px;
        font-family: Commissioner;
        font-style: normal;
        font-weight: 500;
        font-size: 13px;
        line-height: 20px;
        letter-spacing: 0.01em;
        color: rgba(0, 0, 0, 0.75);
    }
    .footer_all_addresses div p:nth-of-type(2){
        position: absolute;
        top: 70px;
        width: 200px;
        height: 40px;
        font-family: Lato;
        font-style: normal;
        font-weight: 300;
        font-size: 13px;
        line-height: 20px;
        color: rgba(0, 0, 0, 0.8);
    }
    .footer_all_addresses div p:nth-of-type(3){
        position: absolute;
        top: 105px;
        width: 200px;
        height: 20px;
        font-family: Lato;
        font-style: normal;
        font-weight: normal;
        font-size: 13px;
        line-height: 20px;
        color: rgba(0, 0, 0, 0.8);
    }
    .footer_minsk_cont{
        position: absolute;
        top:60px;
        width: 200px;
        height: 25px;
        font-family: Commissioner;
        font-style: normal;
        font-weight: normal;
        font-size: 14px;
        line-height: 25px;
        letter-spacing: 0.04em;
        text-transform: uppercase;
        color: rgba(0, 0, 0, 0.75);
    }
    .footer_ph_numbers_only{
        position: absolute;
        left: 0px;
        top: 105px;
        width: 200px;
        height: 60px;
        font-family: Lato;
        font-style: normal;
        font-weight: 300;
        font-size: 13px;
        line-height: 20px;
        color: rgba(0, 0, 0, 0.8);
        padding-right: 80px;
    }
    .footer_adress_only{
        position: absolute;
        top: 185px;
        width: 200px;
        height: 20px;
        font-family: Commissioner;
        font-style: normal;
        font-weight: 500;
        font-size: 13px;
        line-height: 20px;
        letter-spacing: 0.01em;
        color: rgba(0, 0, 0, 0.75);
    }
    .adres_webf{
        position: absolute;
        left: 0px;
        top: 210px;
        width: 200px;
        height: 40px;
        font-family: Lato;
        font-style: normal;
        font-weight: 300;
        font-size: 13px;
        line-height: 20px;
        color: rgba(0, 0, 0, 0.8);
    }
    .rf_rezident_only{
        position: absolute;
        left: 0px;
        top: 270px;
        width: 200px;
        height: 40px;
        font-family: Commissioner;
        font-style: normal;
        font-weight: 500;
        font-size: 13px;
        line-height: 20px;
        letter-spacing: 0.01em;
        color: rgba(0, 0, 0, 0.75);
    }
    .whatsapp_foot{
        position: absolute;
        left: 0px;
        top: 310px;
        width: 200px;
        height: 20px;
        font-family: Lato;
        font-style: normal;
        font-weight: 300;
        font-size: 13px;
        line-height: 20px;
        color: rgba(0, 0, 0, 0.8);
    }
    .down_email_urispr{
        position: absolute;
        left: 0px;
        top: 350px;
        width: 200px;
        height: 20px;
        font-family: Commissioner;
        font-style: normal;
        font-weight: normal;
        font-size: 13px;
        line-height: 20px;
        color: rgba(0, 0, 0, 0.8);
    }
    .footer_opening_hours{
        position: absolute;
        width: 170px;
        height: 335px;
        left: 1375px;
        top: 85px;
    }
    .footer_opening_hours span{
        position: absolute;
        width: 151.79px;
        height: 25px;
        font-family: Lato;
        font-style: normal;
        font-weight: normal;
        font-size: 15px;
        line-height: 25px;
        text-transform: uppercase;
        color: rgba(0, 0, 0, 0.5);
    }
    .footer_opening_hours p:nth-of-type(1){
        position: absolute;
        top: 60px;
        width: 170px;
        height: 20px;
        font-family: Commissioner;
        font-style: normal;
        font-weight: 500;
        font-size: 13px;
        line-height: 20px;
        letter-spacing: 0.01em;
        color: rgba(0, 0, 0, 0.75);
    }
    .footer_opening_hours p:nth-of-type(2){
        position: absolute;
        top: 85px;
        width: 170px;
        height: 60px;
        font-family: Lato;
        font-style: normal;
        font-weight: 300;
        font-size: 13px;
        line-height: 20px;
        color: rgba(0, 0, 0, 0.8);
    }
    .footer_opening_hours p:nth-of-type(3){
        position: absolute;
        top: 175px;
        width: 170px;
        height: 20px;
        font-family: Commissioner;
        font-style: normal;
        font-weight: 500;
        font-size: 13px;
        line-height: 20px;
        letter-spacing: 0.01em;
        color: rgba(0, 0, 0, 0.75);
    }
     .footer_opening_hours p:nth-of-type(4){
        position: absolute;
        top: 200px;
        width: 170px;
        height: 40px;
        font-family: Lato;
        font-style: normal;
        font-weight: 300;
        font-size: 13px;
        line-height: 20px;
        color: rgba(0, 0, 0, 0.8);
     }
    .footer_opening_hours p:nth-of-type(5){
        position: absolute;
        top: 270px;
        width: 170px;
        height: 20px;
        font-family: Commissioner;
        font-style: normal;
        font-weight: 500;
        font-size: 13px;
        line-height: 20px;
        letter-spacing: 0.01em;
        color: rgba(0, 0, 0, 0.75);
    }
    .footer_opening_hours p:nth-of-type(6){
        position: absolute;
        top: 295px;
        width: 170px;
        height: 40px;
        font-family: Lato;
        font-style: normal;
        font-weight: 300;
        font-size: 13px;
        line-height: 20px;
        color: rgba(0, 0, 0, 0.8);
    }
    .footer_ofices hr{
        position: absolute;
        top: 25px;
        width: 640px;
        height: 1px;
        color: rgba(0, 0, 0, 0.1);
        opacity: 0.7;
    }
    .footer_opening_hours hr{
        position: absolute;
        top: 25px;
        width: 170px;
        height: 1px;
        opacity: 0.7;
        color: rgba(0, 0, 0, 0.1);
    }
</style>