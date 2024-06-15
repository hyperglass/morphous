---
layout: page
---

<script setup>
import {
  VPTeamPage,
  VPTeamPageTitle,
  VPTeamMembers
} from 'vitepress/theme'

const members = [
  {
    avatar: 'https://svgshare.com/i/17E4.svg',
    name: 'Rushil',
    title: 'Team Member',
    links: [
      { icon: 'github', link: '' },
      { icon: 'twitter', link: '' }
    ]
  },
  {
    avatar: 'https://svgshare.com/i/17E4.svg',
    name: 'Stefan',
    title: 'Team Member',
    links: [
      { icon: 'github', link: '' },
      { icon: 'twitter', link: '' }
    ]
  },
  {
    avatar: 'https://svgshare.com/i/17E4.svg',
    name: 'Hyde',
    title: 'Team Member',
    links: [
      { icon: 'github', link: '' },
      { icon: 'twitter', link: '' }
    ]
  }
  // Add more members as needed
]

const special_thanks = [
  {
    avatar: 'https://svgshare.com/i/17E4.svg',
    name: 'Name',
    title: 'Title',
    links: [
      { icon: 'github', link: '' },
      { icon: 'discord', link: '' }
    ]
  },
  {
    avatar: 'https://svgshare.com/i/17E4.svg',
    name: 'Name',
    title: 'Title',
    links: [
      { icon: 'github', link: '' },
      { icon: 'mastodon', link: '' }
    ]
  },
  // Add more members as needed
]
</script>

<VPTeamPage>
  <VPTeamPageTitle>
    <template #title>
      Our Team
    </template>
    <template #lead>
      Introducing the Member of Gladious
    </template>
  </VPTeamPageTitle>

  <VPTeamMembers
    :members="members"
  />

  <VPTeamPageTitle>
    <template #title>
      Special Thanks
    </template>
    <template #lead>
      Special thanks to these individuals for their outstanding contributions.
    </template>
  </VPTeamPageTitle>

  <VPTeamMembers
    :members="special_thanks"
  />
</VPTeamPage>
