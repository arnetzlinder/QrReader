

<script setup lang="ts">
import { QrcodeStream } from 'vue-qrcode-reader'
    const onDetect = (result: any) => {
        console.log(result)
    }

</script>

<template>
    <qrcode-stream @detect="onDetect">Scanna QR-kod här</qrcode-stream>
</template>
