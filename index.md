# Name
# Headshot (Photo)
# Job Title or Desired Title
# Job or Desired Job Summary
# Contact Fields (Email, Phone, Social Media)
# Expected Graduation

# Education
# Previous Job Experience
# Skills

# Featured Projects

# Licenses and Certifications
# Courses Taken

# Honors and Awards
# Languages



<style>

.accordion {
  border: 2px solid #DCE6F0;
  border-radius: 10px;
  margin: 5px 0;
}

.accordion-header {
  display: flex;
  padding: 16px;
  cursor: pointer;
  border-radius: 10px;
  background-color: #F3F6FA;
}


.accordion-title {
  flex: 1;
}

.accordion-icon: {
  width: 16px;
}

.accordion-content {
  padding: 16px;
  border-radius: 10px;
}

.accordion-content {
  display: none;
}

.accordion-header:hover{
  background-color: rgba(0, 0, 0, 0.1);
}
</style>


<section id="volunteer-work">

<h1>Volunteer Work</h1>

<div class="accordion">
    <div class="accordion-header">
      <div class="accordion-title">Johnstown Soup Kitchen - <em>September, 2019</em></div>
      <span class="accordion-icon">◀</span>
    </div>
    <div class="accordion-content">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
        <br> <br> <strong>Duties included:</strong>
        <ul>
          <li>Duty 1</li>
          <li>Duty 2</li>
          <li>Duty 3</li>
          <li>Duty 4</li>

        </ul>
    </div>
</div>

<div class="accordion">
    <div class="accordion-header">
      <div class="accordion-title">St. Aloysious Catholic Church - <em>2016-2019<em></div>
      <span class="accordion-icon">◀</span>
    </div>
    <div class="accordion-content">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
        <br> <br> <strong>Duties included:</strong>
        <ul>
          <li>Duty 1</li>
          <li>Duty 2</li>
          <li>Duty 3</li>
          <li>Duty 4</li>

        </ul>
    </div>
</div>

<div class="accordion">
    <div class="accordion-header">
      <div class="accordion-title">Third Volunteer Opportunity</div>
      <span class="accordion-icon">◀</span>
    </div>
    <div class="accordion-content">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
    </div>
</div>

<div class="accordion">
    <div class="accordion-header">
      <div class="accordion-title">Fourth Volunteer Opportunity</div>
      <span class="accordion-icon">◀</span>
    </div>
    <div class="accordion-content">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
    </div>
</div>

<div class="accordion">
    <div class="accordion-header">
      <div class="accordion-title">Fifth Volunteer Opportunity</div>
      <span class="accordion-icon">◀</span>
    </div>
    <div class="accordion-content">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
    </div>
</div>


</section>


<section id="education">

<h1>Education</h1>

<div class="accordion">
    <div class="accordion-header">
      <div class="accordion-title">Bachelor's Degree - <em>2023</em></div>
      <span class="accordion-icon">◀</span>
    </div>
    <div class="accordion-content">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

    </div>
</div>

<div class="accordion">
    <div class="accordion-header">
      <div class="accordion-title">Classes</div>
      <span class="accordion-icon">◀</span>
    </div>
    <div class="accordion-content">
      <ul>
        <li>Class 1</li>
        <li>Class 2</li>
        <li>Class 3</li>
        <li>Class 4</li>
        <li>Class 5</li>
      </ul>

    </div>
</div>

<div class="accordion">
    <div class="accordion-header">
      <div class="accordion-title">Classwork</div>
      <span class="accordion-icon">◀</span>
    </div>
    <div class="accordion-content">
      <ul>
        <li>Classwork 1</li>
        <li>Classwork 2</li>
        <li>Classwork 3</li>
        <li>Classwork 4</li>
      </ul>

    </div>
</div>

</section>

<section id="work-experience">

<h1>Work Experience</h1>

<div class="accordion">
    <div class="accordion-header">
      <div class="accordion-title">Shop N' Save - <em>June, 2021 - September, 2022</em></div>
      <span class="accordion-icon">◀</span>
    </div>
    <div class="accordion-content">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
        <br><br> <strong>Duties included:</strong>
        <ul>
          <li>Duty 1</li>
          <li>Duty 2</li>
          <li>Duty 3</li>
          <li>Duty 4</li>
          <li>Duty 5</li>

        </ul>
    </div>
</div>

</section>


<script>

const accordionHeaders = document.getElementsByClassName('accordion-header');
const accordionContents = document.getElementsByClassName('accordion-content');
const accordionIcons = document.getElementsByClassName('accordion-icon');

for (let i = 0; i < accordionHeaders.length; i++) {
  accordionHeaders[i].addEventListener('click', () => {
    accordionContents[i].style.display = accordionContents[i].style.display == 'block' ? 'none' : 'block';
    accordionIcons[i].innerHTML = accordionContents[i].style.display == 'block' ? '▼' : '◀';
  });
}

</script>
