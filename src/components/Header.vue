<template>
        <header class="header">
            <div class="select_wrap">
            <label for="ln_select">Язык</label>
        <select name="langs" class="ln_select" id="ln_select">
            <option value="rush">Русский</option>
            <option value="engl">English</option>
            <option value="blr">Буларуская мова</option>
        </select>
        </div>

        <img src="../assets/header/icon-eye.png" alt="icon-eye" class="icon_eye">

        <img src="../assets/header/beautiful-logo.png" alt="beautiful logo" class="beauty_logo">

        <div class="phones_wrap">
            <span class="all_phones">+375 (44) 755-01-01</span>
            <a href="/"><img src="../assets/header/A1.png" alt="icon a1" class="a1_icon"></a>
            <a href="/"> <img src="../assets/header/home.png" alt="icon home phone" class="home_icon"></a>
            <a href="/"><img src="../assets/header/viber.png" alt="icon viber" class="viber_icon"></a>  
            <span class="mts_phone">+375 (29) 550-01-01</span>
            <a href="/"> <img src="../assets/header/mts-icon.png" alt="icon mts" class="mts_icon"></a>
        </div>

        <nav class="nav">
                <ul class="header_list">
                    <li class="header_item">
                        <a href="/" class="header_link">ГЛАВНАЯ</a>
                    </li>
                    <li class="header_item">
                        <a href="/" class="header_link">О НАС</a>
                    </li>
                    <li class="header_item">
                        <a href="/" class="header_link">УСЛУГИ</a>
                    </li>
                    <li class="header_item">
                        <a href="/" class="header_link">ТАРИФЫ</a>
                    </li>
                    <li class="header_item">
                        <a href="/" class="header_link">ИНФОЦЕНТР</a>
                    </li>
                    <li class="header_item">
                        <a href="/" class="header_link">КОНТАКТЫ</a>
                    </li>
                </ul>
        </nav>

        <div class="search_icon">
            <a href="/" class="header_logo_link">
                <img src="../assets/header/icon-search.png" alt="search icon" class="">
            </a> 
        </div>
        
        </header>
</template>

<script>
export default {
    name: 'Header',
    props:{

    },
}
</script>

<style scoped>
    .header{
        position: relative;
        left: 0px;
        top: 0px;
        width: 1920px;
        height: 150px;
        background: #FFFFFF;
    }
    .select_wrap{
        position: absolute;
        left: 375px;
        top: 15px;
    }
    .ln_select{
        margin-left: 13px;
    }
    .icon_eye{
        position: absolute;
        left: 944.46px;
        top: 16.56px;
        width: 32,08px;
        height: 21,88px;
    }
    .beauty_logo{
        position: absolute;
        left: 375px;
        top: 71.85px;
        width: 230,77px;
        height: 55.86px;
    }
    .phones_wrap{
        position: absolute;
        left: 1173px;
        top:15px;
        width: 418px;
        height: 20px;
    }
    .all_phones{
        position: absolute;
        left: 0px;
        top: 0px;
        width: 137px;
        text-align: center;
    }
    .a1_icon{
        position: absolute;
        left: 152.15px;
        top: 1.81px;
        width: 17.98px;
        height: 15.19px;
    }
    .home_icon{
        position: absolute;
        left: 183.68px;
        top: 1.25px;
        width: 16.64px;
        height: 17.09px;
    }
    .viber_icon{
        position: absolute;
        left: 212px;
        width: 20px;
        height: 20px;
    }
    .mts_phone{
        position: absolute;
        left: 246px;
        top: 0px;
        width: 137px;
        text-align: center;
    }
    .mts_icon{
        position: absolute;
        left: 398px;
        width: 20px;
        height: 20px;
    }
    .nav{
      position: absolute;
      left: 868px;
      top: 85px;
      width: 670.25px;
      height: 20px;
    }
    .header_list{
      display:flex;
      flex-wrap: nowrap;
      align-items: flex-start;
      justify-content: space-between;
      width: 574px;
   }
   .header_item{
        font-family: Commissioner;
        font-style: normal;
        font-weight: 500;
        font-size: 14px;
        line-height: 20px;
   }
   .header_link{
       text-decoration: none;
       color: rgba(0, 0, 0, 0.75);
   }
   .header_link:hover, .header_link:focus, .header_link:active{
    color:red;
    }
    .search_icon{
        position: absolute;
        left: 1588.86px;
        top: 86.86px;
        width: 16.89px;
        height: 16.89px;
    }
    
</style>