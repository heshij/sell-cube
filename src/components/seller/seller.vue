<template>
  <div>
    I am seller
  </div>
</template>

<script>
  export default {
    name: 'seller'
  }
</script>

<style lang="stylus" scoped>
  @import "~common/stylus/variable"
  @import "~common/stylus/mixin"

  .seller
    height: 100%
    text-align: left
    .overview
      position: relative
      padding: 18px
      .title
        margin-bottom: 8px
        line-height: 14px
        font-size: $fontsize-medium
        color: $color-dark-grey
      .desc
        display: flex
        align-items: center
        padding-bottom: 18px
        .star
          margin-right: 8px
        .text
          margin-right: 12px
          line-height: 18px
          font-size: $fontsize-small-s
          color: $color-grey
      .remark
        display: flex
        padding-top: 18px
        .block
          flex: 1
          text-align: center
          border-right: 1px solid $color-col-line
          &:last-child
            border: none
          h2
            margin-bottom: 4px
            line-height: 10px
            font-size: $fontsize-small-s
            color: $color-light-grey
          .content
            line-height: 24px
            font-size: $fontsize-small-s
            color: $color-dark-grey
            .stress
              font-size: $fontsize-large-xxx
      .favorite
        position: absolute
        width: 50px
        right: 11px
        top: 18px
        text-align: center
        .icon-favorite
          display: block
          margin-bottom: 4px
          line-height: 24px
          font-size: $fontsize-large-xxx
          color: $color-light-grey-s
          &.active
            color: $color-red
        .text
          line-height: 10px
          font-size: $fontsize-small-s
          color: $color-grey
    .bulletin
      padding: 18px 18px 0 18px
      white-space: normal
      .title
        margin-bottom: 8px
        line-height: 14px
        color: $color-dark-grey
        font-size: $fontsize-medium
      .content-wrapper
        padding: 0 12px 16px 12px
        .content
          line-height: 24px
          font-size: $fontsize-small
          color: $color-red
      .supports
        .support-item
          display: flex
          align-items: center
          padding: 16px 12px
          &:last-child
            border-none()
        .support-ico
          margin-right: 6px
        .text
          line-height: 16px
          font-size: $fontsize-small
          color: $color-dark-grey
    .pics
      padding: 18px
      .title
        margin-bottom: 12px
        line-height: 14px
        color: $color-dark-grey
        font-size: $fontsize-medium
      .pic-wrapper
        display: flex
        align-items: center
        .pic-list
          .pic-item
            display: inline-block
            margin-right: 6px
            width: 120px
            height: 90px
            &:last-child
              margin: 0
    .info
      padding: 18px 18px 0 18px
      color: $color-dark-grey
      .title
        padding-bottom: 12px
        line-height: 14px
        font-size: $fontsize-medium
      .info-item
        padding: 16px 12px
        line-height: 16px
        font-size: $fontsize-small
        &:last-child
          border-none()
</style>
