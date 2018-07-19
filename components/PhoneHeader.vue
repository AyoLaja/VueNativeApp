<template>
    <view>
        <image 
            :source="{uri: 'https://s3-us-west-2.amazonaws.com/s.cdpn.io/1211695/vue_gram_logo_cp.png'}"
        />
        <text>
            {{message}}
        </text>
    </view>
</template>

<script>
    export default {
        data() {
            return {
                message: 'Test message'
            }
        }
    }
</script>