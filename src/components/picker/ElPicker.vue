<template>
  <div>
    <div class="bee-mask"></div>
    <div class="bee-picker">
      <div class="bee-picker_hd bee-flexbox">
        <a class="bee-flexbox_item bee-picker__action">取消</a>
        <a class="bee-flexbox_item bee-picker__action">确定</a>
      </div>
      <div class="bee-picker_bd bee-flexbox">
        <div class="bee-picker__group bee-flexbox_item">
          <div class="bee-picker__mask"></div>
          <div class="bee-picker_indicator"></div>
          <div class="bee-picker__content">
            <div class="bee-picker__item">飞机票</div>
            <div class="bee-picker__item">火车票</div>
            <div class="bee-picker__item">的士票</div>
            <div class="bee-picker__item">其他</div>
            <div class="bee-picker__item">其他</div>
            <div class="bee-picker__item">其他</div>
            <div class="bee-picker__item">其他</div>
            <div class="bee-picker__item">其他</div>
            <div class="bee-picker__item">其他</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'picker'
}
</script>
