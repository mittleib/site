<script>
    //↓↓ Images ↓↓
    import Chair from "$lib/images/committee/lucy.jpeg"
    import Treasurer from "$lib/images/committee/mia.jpeg"
    import Secretary from "$lib/images/committee/madz.jpeg"
    import PRO from "$lib/images/committee/zara.jpeg"
    import TechLead from "$lib/images/committee/plooney.jpeg"
    import Amenities from "$lib/images/committee/ayushmaan.jpeg"
    import Competitions from "$lib/images/committee/elizabeth.jpeg"
    import Gaming from "$lib/images/committee/pavit.jpeg"
    import Events from "$lib/images/committee/darragh.jpeg"
    import CoderDojo from "$lib/images/committee/agnetha.jpeg"
    import GeneralOfficer1 from "$lib/images/committee/izzy.jpeg"
    import GeneralOfficer2 from "$lib/images/committee/darren.jpeg"
    import eSports from "$lib/images/committee/keith.jpeg"
    // import DiversityAndInclusion from "$lib/images/committee/elizabeth.jpg"
    import FirstYearRepresentative from "$lib/images/committee/dimitris.jpeg"
    //↑↑ Images ↑↑

import PassportCard from "$lib/components/PassportCard.svelte";
</script>

<div class="about-page">
    <h1>The DUCSS Committee (2025/26)</h1>
    <div class="committee-container">
        <PassportCard name='Lucy Byrne' description='Chair' image={Chair}/>
        <PassportCard name='Mia Rolfe' description='Treasurer' image={Treasurer}/>
        <PassportCard name='Madalina Costovici' description='Secretary' image={Secretary}/>
        <PassportCard name='Braastad-Korhonen' description='PRO' image={PRO}/>
        <PassportCard name='Plooney' description='Tech Lead' image={TechLead}/>
        <PassportCard name='Elizabeth Gogová' description='Competitions' image={Competitions}/>
        <PassportCard name='Pavit Gogia' description='Gaming' image={Gaming}/>
        <PassportCard name='Darragh Condron' description='Events' image={Events}/>
        <PassportCard name='Agnetha Kamath' description='CoderDojo' image={CoderDojo}/>
        <PassportCard name='Izzy Guey' description='General Officer' image={GeneralOfficer1}/>
        <PassportCard name='Darren McCabe' description='General Officer' image={GeneralOfficer2}/>
        <PassportCard name='Keith Lyons' description='eSports' image={eSports}/>
        <!-- <PassportCard name='' description='Diversity & Inclusion' image={DiversityAndInclusion}/> -->
        <PassportCard name='Ayushmaan Kumar Yadav' description='Amenities' image={Amenities}/>
        <PassportCard name='Dmitiris Charalampakis' description='First Year Rep' image={FirstYearRepresentative}/>
    </div>
</div>

<style>
    * {
        font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    }

    .about-page {
        text-align: center;
        padding: 16px;
    }

    h1 {
        text-align: center;
        font-size: 36px;
        font-weight: 700;
        letter-spacing: -0.05em;
        
        margin-bottom: 24px;
        color: hsl(209, 15%, 20%);
    }

    .committee-container {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); 
        gap: 24px;
        padding: 16px;
    }

    @media (max-width: 600px) {
        h1 {
            font-size: 2.25rem;
        }

        .committee-container {
            gap: 32px;
        }
    }
</style>

