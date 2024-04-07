<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Biodata Diri</template>
    Perkenalkan nama saya Zakia Aulia Putra, saya biasa di panggil Zakia. Saya merupakan seorang mahasiswa semester 4 jurusan 
    <a href="https://www.instagram.com/fakultasteknikuir?utm_source=ig_web_button_share_sheet&igsh=ZDNlZDc0MzIxNw==" target="_blank" rel="noopener">Teknik Informatika</a> di  <a href="https://uir.ac.id/" target="_blank" rel="noopener">Universitas Islam Riau</a>. 
    Saya Lahir di Solok Pada tanggal 07 Januari 2004, Asal saya dari Alahan panjang Sumatra barat. saya tamatan dari <a href="https://www.instagram.com/smansalg22?igsh=emNreHd5azdnOXpm" target="_blank" rel="noopener">SMAN 1 Lembah Gumanti</a> dengan jurusan IPA
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Skill dan Kemampuan</template>
    Saya memiliki beberapa kemampuan Inter Personal diantara nya ialah  <a href="https://uir.ac.id/" target="_blank" rel="noopener">Leadership</a>,  <a href="https://uir.ac.id/" target="_blank" rel="noopener">Pembicara publik</a>,  <a href="https://uir.ac.id/" target="_blank" rel="noopener">Berdiskusi</a>,  <a href="https://uir.ac.id/" target="_blank" rel="noopener">Interaksi Sosial</a>, Disiplin, Amamanah
    , Teliti dan Tekun, Bertanggung Jawab. Saya juga Mempunyai 3 Keahlian bahasa yaitu Bahasa indonesia, Inggris, dan Arab.

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Pengalaman</template>
    Pengalaman Saya lebih berpatokan pada Pengalaman Non-Academic Yaitu pengalaman beroganisasi, dan pengalaman berorganisasi ini saya bagi menjadi
    2 yaitu organisasi internal dan eksternal, dimulai dari internal. Yang pertama yaitu Ketua Osim MTSM Al- Mumtaz, Pramuka Internasional Istano basa pagaruyuang,
    Ketua IPMA Ponpes Al- Mumtaz, Ketua Angkatan SMA Negeri 1 Lembah Gumanti, Ketua angkatan Universitas islam Riau angkatan 2022, Organisasi Eksternal nya yaitu Latihan
    Kader 1 Himpunan Mahasiswa Islam.  
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
      </template>
    <template #heading>Follow Me</template>
    <ul class="social-media-icons">
      <li><a href="#"><img src="@/assets/Facebook-icon.png" alt="Facebook"></a></li>
      <li><a href="#"><img src="@/assets/twitter-icon.png" alt="Twitter"></a></li>
      <li><a href="https://www.instagram.com/zakiaauliaputra?utm_source=ig_web_button_share_sheet&igsh=ZDNlZDc0MzIxNw=="><img src="@/assets/instagram-icon.png" alt="Instagram"></a></li>
    </ul>
  </WelcomeItem>
</template>

<style scoped>
.social-media-icons {
  list-style: none;
  padding: 0;
  margin: 0;
  display: flex;
  gap: 10px; 
}

.social-media-icons li {
  display: inline-block;
}

.social-media-icons img {
  width: 30px; /* Lebar ikon */
  height: 30px; /* Tinggi ikon */
}
</style>