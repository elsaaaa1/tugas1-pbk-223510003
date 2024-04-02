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
      <TENTANG DIRI SAYAIcon />
    </template>
    <template #heading>TENTANG DIRI SAYA</template>

  
    <a href="https://vuejs.org/" target="_blank" rel="noopener"></a>
    Saya seorang mahasiswa Universitas Islam Riau dari Jurusan Teknik Informatika yang sekarang berada disemester 4.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <DATA PRIBADIIcon />
    </template>
    <template #heading>DATA PRIBADI</template>
    Nama : Dina fitria ain
    <br> Npm : 223510003
    <br> Tempat/tgl.lahir : Muara intan, 8 desember 2002
    <br> Jenis Kelamin : Perempuan

    <br />

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <PENDIDIKANIcon />
    </template>
    <template #heading>PENDIDIKAN</template>
    SDN 015 kunto darusallam
    <br> SMPN 3 kunto darusallam
    <br> SMKS islam inayah ujung batu

  </WelcomeItem>

  
   <WelcomeItem>
    <template #icon>
      <HOBIIcon />
    </template>
    <template #heading> HOBI </template>
    Menonton film/drakor
    <br> Mendengar Musik

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CONTACTIcon />
    </template>
    <template #heading>CONTACT</template>
    <br> Instagram : yanaaiin__
    <br> Email : 

    
  </WelcomeItem>
</template>
