<template>
    <main>
      <section>
        <div class="container">
          <div class="row row-cols-auto mx-auto mt-3">
             <div class="col">
               <img alt="jocka-jpg" src="../assets/images/jocka-image.jpg" width="120" height="120"/>
             </div>
             <div class="col">
               <h4>Jordan Velkovski</h4>
               <span>Full-stack Developer</span>
             </div>
          </div>
          <div class="row mt-5 ">
            <div class="col col-11 ">
              <ul class="list-inline">
                <li class="list-inline-item fs-6"><i class="fa fa-user fa-2x" aria-hidden="true"></i></li>
                <li class="list-inline-item fs-4 fw-bolder">Profile</li>
              </ul>
            </div>
            <div class="col col-9">
              <p>{{ stringShortTextLorem }}</p>
            </div>
          </div>
          <div class="row">
            <div class="col col-11 mb-0">
              <ul class="list-inline mb-0">
                <li class="list-inline-item fa-2x fs-3"><i class="fa fa-suitcase" aria-hidden="true"></i></li>
                <li class="list-inline-item fs-4 fw-bolder">Employment history</li>
                <h6>Participant at Bike Computer Co</h6>
                <p class="mb-1"><small>July 2022 - Present</small></p>
              </ul>
              <p class="fs-6">{{ stringShortTextLorem }}</p>
            </div>
          </div>
          <div class="row mt-3">
            <div class="col col-11">
              <ul class="list-inline mb-0">
                <h6>Full stack developer for my needs</h6>
              </ul>
              <p class="fs-6 mb-0">{{ stringLongerTextLorem }}</p>
            </div>
          </div>
          <div class="row mt-3">
            <div class="col col-11">
              <ul class="list-inline mb-0">
                <h6 class="mb-0">Skills</h6>
              </ul>
              <p class="fs-6">
              <div class="d-flex align-items-center">
              <span class="justify-content-between">{{ BS }}</span>
                <div class="ratings ms-3">
                  <i class="fa fa-star rating-color"></i>
                  <i class="fa fa-star rating-color"></i>
                  <i class="fa fa-star rating-color"></i>
                </div>
              </div>
              </p>
              <p class="fs-6">
              <div class="d-flex align-items-center">
                <span class="justify-content-between">{{ JS }}</span>
                <div class="ratings ms-3">
                  <i class="fa fa-star rating-color"></i>
                  <i class="fa fa-star rating-color"></i>
                  <i class="fa fa-star rating-color"></i>
                  <i class="fa fa-star rating-color"></i>
                  <i class="fa fa-star rating-color"></i>
                </div>
              </div>
              </p>
              <p class="fs-6">
              <div class="d-flex align-items-center">
                <span class="justify-content-between">{{ HTML }}</span>
                <div class="ratings ms-3">
                  <i class="fa fa-star rating-color"></i>
                  <i class="fa fa-star rating-color"></i>
                  <i class="fa fa-star rating-color"></i>
                  <i class="fa fa-star rating-color"></i>
                  <i class="fa fa-star rating-color"></i>
                </div>
              </div>
              </p>
              <p class="fs-6">
              <div class="d-flex align-items-center">
                <span class="justify-content-between">{{ CSS }}</span>
                <div class="ratings ms-3">
                  <i class="fa fa-star rating-color"></i>
                  <i class="fa fa-star rating-color"></i>
                  <i class="fa fa-star rating-color"></i>
                  <i class="fa fa-star rating-color"></i>
                  <i class="fa fa-star rating-color"></i>
                </div>
              </div>
              </p>
              <p class="fs-6">
              <div class="d-flex align-items-center">
                <span class="justify-content-between">{{ SQL }}</span>
                <div class="ratings ms-3">
                  <i class="fa fa-star rating-color"></i>
                  <i class="fa fa-star rating-color"></i>
                  <i class="fa fa-star rating-color"></i>
                </div>
              </div>
              </p>
            </div>
          </div>
        </div>
      </section>
    </main>
</template>
<script>
 export default {
   name: 'Body',
   data(){
     return {
       CSS : 'CSS',
       SQL : 'SQL',
       HTML : 'HTML',
       BS : 'BootStrap',
       JS : 'JavaScript',
       stringShortTextLorem : 'Lorem Ipsum is simply dummy text of the printing and typesetting industry.\n' +
           '                Lorem Ipsum has been the industry\'s standard dummy text ever since the 1500s,\n' +
           '                when an unknown printer took a galley of type and scrambled it to make a type specimen book.',
       stringLongerTextLorem : 'Lorem Ipsum is simply dummy text of the printing and typesetting industry.\n' +
           '                Lorem Ipsum has been the industry\'s standard dummy text ever since the 1500s,\n' +
           '                when an unknown printer took a galley of type and scrambled it to make a type specimen book.\n' +
           '                It has survived not only five centuries, but also the leap into electronic typesetting,\n' +
           '                remaining essentially unchanged.\n' +
           '                It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages,\n' +
           '                and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.'
     }
   }
 }
</script>
