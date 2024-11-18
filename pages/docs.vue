<script setup lang="ts">
definePageMeta({
  title: 'About use-bootstrap',
  description: 'Quickly get a project started with any of our examples ranging from using parts of the framework to custom components and layouts.'
})
</script>

<template>
  <Background video-src="/pexels/movie/3209211-uhd_3840_2160_25fps.mp4" :overlay="true" overlay-color="gray-100">
    <b-h level="1" margin="5" display-headings="1" text-color="white">
      <b-p text-color="blue">usebootstrap was</b-p>
      <Typed class="text-primary fw-semibold" :strings="['powerful.', 'extensible.', 'feature-packed.','unreachable']"
        :type-speed="60" :loop="true" :back-speed="30" :back-delay="1500" />
    </b-h>
  </Background>
  <h2>っここは謎のページだよ</h2>
  <h2>楽しんでよー</h2>
  <p>僕の名前は田和氏だよ。平和を愛し恋に焦がれて人生を楽しんでるよ！？</p>
</template>