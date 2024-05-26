<template>
  <!-- Header -->
  <Heading tempID="projects" heading="Projects" headingNum="02"></Heading>

  <Tile
    flip="true"
    special="true"
    title="Car Rental Web App (Frontend)"
    description="An intuitive Front-End side for the car rental website, designed to allow users to browse the available car catalog easily and quickly."
    :languages="['Bootstrap', 'ReactJS', 'Redux']"
    gitLink="https://github.com/nidaftrnie/24001085-km6-nid-react-ch6"
    exLink=""
    imageURL="/images/frontend.png"
  ></Tile>

  <Tile
    special="true"
    title="Car Rental Web App (Backend)"
    description="A backend of a car rental website created by JavaScript and PostgreSQL relational database, developed with the application of clean architecture to build a stable and manageable API."
    :languages="[
      'NodeJS',
      'ExpressJS',
      'PostgreSQL',
      'Google Cloud Platform (GCP)',
      'Redis',
    ]"
    gitLink="https://github.com/nidaftrnie/24001085-km6-nid-auth-ch5"
    exLink=""
    imageURL="images/backend.png"
  ></Tile>

  <Tile
    flip="true"
    title="JejakSiKecil Website"
    jobdesk="Fullstack Developer"
    description="The Connect 4 game is a classic strategy game in which players alternately place pieces on a grid. It is terminal based and built using C programming language. "
    :languages="['PHP', 'Bootstrap', 'MySQL', 'JavaScript']"
    gitLink="https://github.com/AkosoCodes/Travel-Agency-Frontend"
    exLink=""
    imageURL="images/connectfour.png"
  ></Tile>

  <Tile
    special="true"
    title="Election Website"
    description="loremipsum"
    :languages="[
      'NodeJS',
      'ExpressJS',
      'PostgreSQL',
      'Redis',
      'Google Cloud Platform (GCP)',
      'ReactJS',
      'Tailwind',
    ]"
    gitLink="https://github.com/orgs/team-3-binar-fsw-msib-6/repositories"
    exLink=""
    imageURL="/images/theme1.png"
  ></Tile>

  <Tile
    flip="true"
    title="DaurUlangin Website"
    jobdesk="UI/UX Designer"
    description="The Connect 4 game is a classic strategy game in which players alternately place pieces on a grid. It is terminal based and built using C programming language. "
    :languages="['Figma']"
    gitLink="https://www.figma.com/proto/zUszu2E1ZBIsvFvgjHFNRM/Garbage-Classification?page-id=36%3A14&node-id=438-577&starting-point-node-id=438%3A577&t=e5TnL7H5iAm7Hh5h-1"
    exLink=""
    imageURL="images/connectfour.png"
  ></Tile>
</template>

<script>
import Heading from "../heading.vue";
import Tile from "../tile.vue";

export default {
  name: "projects",
  components: {
    Heading,
    Tile,
  },
};
</script>
