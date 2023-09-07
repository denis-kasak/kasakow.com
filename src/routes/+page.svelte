<script lang="ts">
  import Links from "$lib/Links.svelte";
</script>

<div class="h-full flex flex-col lg:flex-row justify-center gap-2">
  <div class="lg:basis-1/2">
    <div class="h-full flex flex-col w-full justify-center">
      <div class="flex flex-col gap-4">
        <div class="h-96 mx-auto">
          <img src="/photo.jpg" class="max-h-full" alt="Denis" />
        </div>
        <div class="mx-auto text-center w-max">
          <h1 class="h1">Denis Alexej Kasakow</h1>
          <h2 class="h2">IT Specialist</h2>
        </div>
      </div>
    </div>
  </div>
  <div class="basis-1/2 pt-4 lg:pt-0">
    <div class="h-full flex flex-col items-center lg:justify-center gap-2">
      <div class="flex flex-col gap-6">
        <div class="flex flex-col">
          <h3 class="h4 lg:h3">
            Computer Science (B.Sc.) Student
            <br />
            @
            <a class="anchor" href="https://www.hwr-berlin.de/">
              Berlin School of Economics and Law</a
            >
          </h3>
          <h3 class="h4 lg:h3">
            Junior SAP ABAP Software Engineer
            <br /> @
            <a class="anchor" href="https://www.mercoline.de/">Mercoline GmbH</a
            >
          </h3>
          <h3 class="h4 lg:h3">
            SAP Certified Application Associate Certification
            <br /> @
            <a class="anchor" href="https://www.erp4students.de/"
              >ERP4Students</a
            >
          </h3>
        </div>
        <Links />
      </div>
    </div>
  </div>
</div>

<style>
  img {
    border-radius: 10%;
  }
</style>
