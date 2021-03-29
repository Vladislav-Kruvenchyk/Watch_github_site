<template>
    <div class="header">
        <div class="block">
           <ul class="block_wrap">
               <li class="block_inner_phone"></li>
               <li class="block_inner_figure">8 (812) 123-45-67 |</li>
               <li class="block_inner_speech">Работаем 7 дней в неделю |</li>
               <li class="block_inner_clock">9:00 — 18:00</li>
            </ul> 
        </div>
        <div class="block-two">
            <ul class="block-wrapper">
                <li class="block_item_entranse"></li>
                <li class="block_item_entranse_two"></li>
                <li class="block_item">Войти /</li>
                <li class="block_item_two">Регистрация</li>
            </ul>
        </div>
    </div>
</template>

<script>


export default {
    name: 'header',
    components: {
    }
}
</script>


<style lang="scss" scoped>

.block_inner_phone {
    background: url('../assets/img/block_header/icon/phone.png');
    background-size: cover;
    width: 17px;
    height: 17px;
    margin-right: 1rem;
}

.block_item_entranse {
    overflow: hidden;
    background: url('../assets/img/block_header/icon/entranse.png');
    background-size: cover;
    width: 8px;
    height: 6px;
    transform: translateX(4px);
}

.block_item_entranse_two {
    overflow: hidden;
    background: url('../assets/img/block_header/icon/entranse_two.png');
    background-size: cover;
    margin-right: 10px;
    width: 8px;
    height: 12px;
}
.block_inner_figure {
    border-left: 2px solid  #969696;
    text-align: center;
    align-items: center;
    width: 9rem;
    height: 18px;
}
.block_inner_speech {
    border-left: 2px solid  #969696;
    text-align: center;
    align-items: center;
    width: 13rem;
    height: 18px;
}
.block_inner_clock {
    border-left: 2px solid  #969696;
    text-align: center;
    align-items: center;
    width: 7rem;
    height: 18px;
}
.header {
    display: flex;
    min-height: 40px;
    width: 100%;
    background: #0F0F0F;
}
.block {
    display: flex;
    width: 50%;
    height: 44px;    
}
.block_wrap {
    display: flex;
    width: 1920px;
    height: 44px;
    justify-content: flex-end;
    text-align: center;
    align-items: center;
    font-family: PT Sans;
    font-style: normal;
    font-weight: normal;
    font-size: 12px;
    line-height: 16px;
    color: #969696;
    margin-right: 1rem;
}
.block-two {
    display: flex;
    width: 50%;
    height: 44px;
}
.block-wrapper {
    display: flex;
    align-items: center;
    text-align: center;
    justify-content: center;
}
.block_item {
    width: 44px;
    height: 1rem;
    font-family: 'PT Sans';
    font-style: normal;
    font-weight: normal;
    font-size: 12px;
    line-height: 16px;
    color: #969696;
}
.block_item_two {
    width: 87px;
    height: 1rem;
    font-family: 'PT Sans';
    font-style: normal;
    font-weight: normal;
    font-size: 12px;
    line-height: 16px;
    text-align: start;
    color: #969696;
    margin-right: 8px;
}

</style>