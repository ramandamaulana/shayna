<template>
  <div class="home">
    <HeaderShayna />
    <ContentShayna />
    <BannerShayna />
    <InstaShayna />
    <PartnerShayna />
    <FooterShayna />
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderShayna from "@/components/HeaderShayna.vue";
import ContentShayna from "@/components/ContentShayna.vue";
import BannerShayna from "@/components/BannerShayna.vue";
import InstaShayna from "@/components/InstaShayna.vue";
import PartnerShayna from "@/components/PartnerShayna.vue";
import FooterShayna from "@/components/FooterShayna.vue";

export default {
  name: "Home",
  components: {
    HeaderShayna,
    ContentShayna,
    BannerShayna,
    InstaShayna,
    PartnerShayna,
    FooterShayna
  }
};
</script>
