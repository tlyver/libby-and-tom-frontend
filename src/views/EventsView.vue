<script setup lang="ts">

import WelcomeItem from '../components/WelcomeItem.vue'
import EventsHeading from '../components/EventsHeading.vue'
import Address from '../components/Address.vue'
import EventsBody from '../components/EventsBody.vue'
import DocumentationIcon from '../components/icons/IconDocumentation.vue'
import ToolingIcon from '../components/icons/IconTooling.vue'
import EcosystemIcon from '../components/icons/IconEcosystem.vue'
import CommunityIcon from '../components/icons/IconCommunity.vue'
import SupportIcon from '../components/icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #heading>
      <EventsHeading
        title="Welcome Drinks"
        subtitle="Fri, Aug 16, 2023 8:00 pm"
        />
    </template>

    <EventsBody>
      <template #icon>
        <DocumentationIcon />
      </template>

      <Address
        name="Talea Beer Co."
        address1="61 Bergen St"
        city="Brooklyn"
        state="NY"
        zip="11201"
      >
      </Address>
    </EventsBody>
  </WelcomeItem>

  <WelcomeItem>
    <template #heading>
      <EventsHeading
        title="Ceremony"
        subtitle="Sat, Aug 17, 2023 2:00 pm"
        />
    </template>

    <EventsBody>
      <template #icon>
        <DocumentationIcon />
      </template>

      <Address
        name="St. Francis Xavier Church"
        address1="225 6th Ave"
        city="Brooklyn"
        state="NY"
        zip="11215"
      >
      </Address>
    </EventsBody>
  </WelcomeItem>

  <WelcomeItem>
    <template #heading>
      <EventsHeading
        title="Reception"
        subtitle="Sat, Aug 17, 2023 5:00 - 10:00 pm"
        />
    </template>

    <EventsBody>
      <template #icon>
        <DocumentationIcon />
      </template>

      <Address
        name="Brooklyn Grange"
        address1="850 Third Ave"
        address2="Roof"
        city="Brooklyn"
        state="NY"
        zip="11232"
      >
      </Address>
    </EventsBody>
  </WelcomeItem>
</template>
