<script>
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
</script>

<div class="about-page">
    <h1>The DUCSS Committee (2024/25)</h1>
    <div class="committee-container">
        <div class="committee-member">
            <h2>Chair</h2>
            <h3>Darragh Condron</h3>
            <img class="committee-member-image" src={Chair} alt="Chair" />
        </div>
        <div class="committee-member">
            <h2>Treasurer</h2>
            <h3>Manuel Araújo</h3>
            <img class="committee-member-image" src={Treasurer} alt="Treasurer" />
        </div>
        <div class="committee-member">
            <h2>Secretary</h2>
            <h3>Mia Rolfe</h3>
            <img class="committee-member-image" src={Secretary} alt="Secretary" />
        </div>
        <div class="committee-member">
            <h2>PRO</h2>
            <h3>Lucy Byrne</h3>
            <img class="committee-member-image" src={PRO} alt="Public Relations Officer"/>
        </div>
        <div class="committee-member">
            <h2>Tech Lead</h2>
            <h3>James Doyle</h3>
            <img class="committee-member-image" src={TechLead} alt="Tech Lead" />
        </div>
        <div class="committee-member">
            <h2>Amenities</h2>
            <h3>Madalina Costovici</h3>
            <!-- <img class="committee-member-image" src={Treasurer} alt="Treasurer"/> -->
        </div>
        <div class="committee-member">
            <h2>Competitions</h2>
            <h3>Ross Devine</h3>
            <img class="committee-member-image" src={Competitions} alt="Competitions" />
        </div>
        <div class="committee-member">
            <h2>Gaming</h2>
            <h3>Ralf Duli</h3>
            <img class="committee-member-image" src={Gaming} alt="Gaming" />
        </div>
        <div class="committee-member">
            <h2>Events</h2>
            <h3>Daniel Guerin</h3>
            <img class="committee-member-image" src={Events} alt="Events" />
        </div>
        <div class="committee-member">
            <h2>CoderDojo</h2>
            <h3>Siddhi Srivastav</h3>
            <img class="committee-member-image" src={CoderDojo} alt="CoderDojo" />
        </div>
        <div class="committee-member">
            <h2>General Officer</h2>
            <h3>Ciara Quinn</h3>
            <img class="committee-member-image" src={GeneralOfficer1} alt="General Officer" />
        </div>
        <div class="committee-member">
            <h2>General Officer</h2>
            <h3>Ellie Smith</h3>
            <img class="committee-member-image" src={GeneralOfficer2} alt="General Officer" />
        </div>
        <div class="committee-member">
            <h2>eSports</h2>
            <h3>Rohn Allen Santiago</h3>
            <img class="committee-member-image" src={eSports} alt="eSports" />
        </div>
        <div class="committee-member">
            <h2>D&I</h2>
            <h3>Elizabeth Gogova</h3>
            <img class="committee-member-image" src={DiversityAndInclusion} alt="Diversity & Inclusion" />
        </div>
        <div class="committee-member">
            <h2>First Year Rep</h2>
            <h3>Zara Braastad-Korhonen</h3>
            <img class="committee-member-image" src={FirstYearRepresentative} alt="First Year Representative"/>
        </div>
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
        font-size: 2.5rem;
        margin-bottom: 24px;
    }

    .committee-container {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); 
        gap: 24px;
        padding: 16px;
    }

    .committee-member {
        background-color: hsla(208, 12%, 95%, 1.0);
        border: 1px solid hsl(208, 12%, 85%);
        border-radius: 12px;
        padding: 24px;
        text-align: center;
        box-shadow: 0 6px 8px rgba(0, 0, 0, 0.15);
    }

    h2 {
        color: hsl(35, 95%, 58%);
        font-size: 1.5rem;
        margin-bottom: 12px;
    }

    h3 {
        font-size: 1.125rem;
        margin-bottom: 20px;
    }

    .committee-member-image {
        width: 200px;
        height: 200px; 
        object-fit: cover;
        border-radius: 12px;
        border: 3px solid hsl(35, 95%, 58%);
    }

    @media (max-width: 600px) {
        h1 {
            font-size: 2.25rem;
        }

        .committee-member {
            padding: 32px;
        }

        h2 {
            font-size: 2.5rem;
        }

        h3 {
            font-size: 1.5rem;
        }

        .committee-member-image {
            width: 250px;
            height: 250px;
        }

        .committee-container {
            gap: 32px;
        }
    }
</style>

