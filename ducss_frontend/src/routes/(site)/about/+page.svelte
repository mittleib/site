<script>
    //↓↓ Images ↓↓
    import Chair from "$lib/images/committee/darragh.jpg"
    import Treasurer from "$lib/images/committee/manel.jpg"
    import Secretary from "$lib/images/committee/mia.jpg"
    import PRO from "$lib/images/committee/lucy.jpg"
    import TechLead from "$lib/images/committee/james.jpg"
    // import Amenities from "$lib/images/committee/"
    import Competitions from "$lib/images/committee/ross.jpg"
    import Gaming from "$lib/images/committee/ralf.jpg"
    import Events from "$lib/images/committee/dan.jpg"
    import CoderDojo from "$lib/images/committee/siddhi.jpg"
    import GeneralOfficer1 from "$lib/images/committee/ciara.jpeg"
    import GeneralOfficer2 from "$lib/images/committee/ellie.png"
    import eSports from "$lib/images/committee/rohn.jpg"
    import DiversityAndInclusion from "$lib/images/committee/elizabeth.jpg"
    import FirstYearRepresentative from "$lib/images/committee/zara.jpg"
    //↑↑ Images ↑↑

import PassportCard from "$lib/components/PassportCard.svelte";
</script>

<div class="about-page">
    <h1>The DUCSS Committee (2025/26)</h1>
    <div class="committee-container">
        <PassportCard name='Darragh Condron' description='Chair' image={Chair}/>
        <PassportCard name='Manuel Araújo' description='Treasurer' image={Treasurer}/>
        <PassportCard name='Mia Rolfe' description='Secretary' image={Secretary}/>
        <PassportCard name='Lucy Byrne' description='PRO' image={PRO}/>
        <PassportCard name='James Doyle' description='Tech Lead' image={TechLead}/>
        <PassportCard name='Madalina Costovici' description='Amenities'/>
        <PassportCard name='Ross Devine' description='Competitions' image={Competitions}/>
        <PassportCard name='Ralf Duli' description='Gaming' image={Gaming}/>
        <PassportCard name='Daniel Guerin' description='Events' image={Events}/>
        <PassportCard name='Siddhi Srivastav' description='CoderDojo' image={CoderDojo}/>
        <PassportCard name='Ciara Quinn' description='General Officer' image={GeneralOfficer1}/>
        <PassportCard name='Ellie Smith' description='General Officer' image={GeneralOfficer2}/>
        <PassportCard name='Rohn Allen Santiago' description='eSports' image={eSports}/>
        <PassportCard name='Elizabeth Gogova' description='Diversity & Inclusion' image={DiversityAndInclusion}/>
        <PassportCard name='Zara Braastad-Korhonen' description='First Year Rep' image={FirstYearRepresentative}/>
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

