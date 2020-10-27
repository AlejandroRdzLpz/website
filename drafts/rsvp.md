---
title: "RSVP to #LHM Summit"
description: "Attend Techqueria's first virtual summit and celebrate the thriving Latinx in tech community."
image: "/assets/img/summit/2020/rsvp/rsvp.png"
noTimeEstimate: true
hideImage: true
aliases:
  - /summit/rsvp/
  - /summit/tickets/
---

<form name="RSVP to #LHM Summit" method="POST" data-netlify-recaptcha="true" data-netlify="true" action="/success/summit/" class="form--centered mt-2 no-ids" id="form_rsvp_lhm_summit">
  <input type="hidden" aria-label="Subject" name="_subject" value="Techqueria - RSVP to #LHM Summit">
  <!-- First Name + Last Name -->
  <div class="field mt-0 mb-1">
    <div class="columns mb-0">
      <div class="column pb-0">
        <!-- First Name -->
        {{< fields/name_first >}}
      </div>
      <div class="column pb-0">
        <!-- Last Name -->
        {{< fields/name_last >}}
      </div>
    </div>
  </div>
  {{< fields/email >}}
  {{< fields/organization label="Where do you currently work or study?" >}}
  {{< fields/title label="What is your current role?" help="e.g. Software Engineer, UX Designer, Product Manager, Student, etc." >}}
  {{< fields/linkedin >}}
  {{< fields/yoe >}}
  {{< fields/resume help="If you're looking for a new job, you can share your resume with our sponsors and they'll reach out if there's a good fit. Please upload a 1-page PDF file." >}}
  {{< fields/job_category >}}
  {{< fields/job_searching >}}
  {{< fields/pronouns >}}
  {{< fields/latinx >}}
  {{< fields/disclaimer >}}
  {{< fields/submit label="RSVP to #LHM Summit" >}}
</form>
<script src="/assets/js/rsvp.js"></script>
