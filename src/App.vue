<router-link class="" to="/"></router-link> 
<router-view/>
  <template>
  <div class="bg-blue-900 h-32 md:h-24 text-white flex flex-row justify-between items-center px-4">
        <h1 class=" text-xs md:text-sm" >1b, unity estate, ota, Ogun State, Nigeria</h1>
        <div class="flex flex-col md:flex-row gap-3">
        <h1 class="text-xs md:text-sm" >+2348055462792</h1>
        <h1 class="text-xs md:text-sm" >+2348034339970</h1>
      </div>
      <div>
      <h1 class=" text-sm md:text-lg text-gray-200 animate-bounce " >ADMISSION IS OPEN!!!</h1>
      <button type="text" class="bg-white rounded-lg w-20 md:w-32 h-8 text-blue-500 text-xs md:text-sm" >REGISTER NOW!!</button>
    </div>
      </div>
    <nav class="bg-white p-2">
      
      <div class="container mx-auto d-flex justify-between items-center">
        <a href="#" 
        class="text-blue-500 text-lg md:text2xl font-semibold">OXBRIDGE ACADEMY</a>
        <button @click="toggleMenu" class="text-blue-500"> 
          <i class="bi bi-list text-2xl"></i>
        </button>
      </div>
    </nav>

    <div :class="menuOpen ? 'translate-x-0' : 'translate-x-full'" class="fixed top-0 right-0 w-2/3 md:w-1/4 h-full bg-blue-900 text-white transition-transform transform z-50" >
      <div class="p-4 flex justify-between items-center">
        <span class="text-blue-500 text-lg font-semibold md:text-2xl"> OXBRIDGE</span>
        <button @click="toggleMenu" class="text-gray-400"> 
          <i class="bi bi-x text-2xl"></i>
        </button>
      </div>
      <ul class="p-4 space-y-4">
        <li><a href="#"
          class="text-gray-300" hover:text-white >About</a>
        </li>
        <li><a href="#"
          class="text-gray-300" hover:text-white >Admission/register</a>
        </li>
        <li><a href="#"
          class="text-gray-300" hover:text-white >Why oxbridge Academy</a>
        </li>
        <li><a href="#"
          class="text-gray-300" hover:text-white >Contact</a>
        </li>
      </ul>
    </div>
    <div v-if="menuOpen" @click="toggleMenu" class="fixed inset-0 bg-black opacity-50 z-40">
    </div>

    <div id="carouselExampleDark" class="carousel carousel-dark slide ">
  <div class="carousel-inner">
  <div class="carousel-item active" data-bs-interval="10000">
    <img src="https://cdn.dribbble.com/userupload/13091128/file/original-7acef7f5b032e240148188cd41039198.jpg?resize=752x496" class="d-block w-full h-[600px] md:h-[800px]">
    <div class="carousel-caption absolute inset-0 flex items-center justify-center text-white">
      <div class="text-center">
        <h5 class="text-xl md:text-3xl font-bold text-black animate-bounce ">Parents paying visit to their various kids at hostel</h5>
      </div>
    </div>
  </div>
  <div class="carousel-inner">
    <div class="carousel-item active" data-bs-interval="2000">
      <img src="https://cdn.dribbble.com/users/1731254/screenshots/14205960/media/c98e1ce5d122a674b3d34f4dfe0e753b.png?resize=640x480&vertical=center" class="d-block w-full h-[600px] md:h-[800px]">
      <div class="carousel-caption absolute inset-0 flex items-center justify-center text-white">
        <div class="text-center">
          <h5 class="text-xl md:text-3xl font-bold text-black animate-bounce ">Elementary Kids having fun in the school bus</h5>
      </div>
      </div>
    </div>
  </div>
  <div class="carousel-inner">
    <div class="carousel-item absolute inset-0 flex items-center justify-center text-white">
      <img src="https://cdn.dribbble.com/users/59947/screenshots/5887643/muti-1a.jpg?resize=640x480&vertical=center" class="d-block w-full h-[600px] md:h-[800px]">
    </div>
  </div>
</div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="prev">
    <span class="carousel-control-prev-icon bg-black" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="next">
    <span class="carousel-control-next-icon bg-black" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>
<div class="container bg-white h-[1300px] md:h-[1400px] lg:h-[900px]">
  <div class="flex flex-col md:flex-row gap-10 mt-5" >
    <img src="https://cdn.dribbble.com/userupload/16393801/file/original-0fad0f05274143d4a74101273105c3ac.png?resize=752x564" 
    class="w-[400px] h-[300px] md:h-[700px] lg:h-[400px] rounded-lg border-2 border-blue-800 ">
    <div class="flex flex-col">
      <h1 class="text-5xl text-blue-800 font-bold">WELCOME TO OXBRIDGE ACADEMY, OTA</h1>
      <h1 class="text-lg text-red-400 " >MOTTO: knowledge is light</h1>
      <h1 class="text-lg text-black " >Oxbridge was established in 2010 as a worldwide school that dosent discriminate in any way... and  that is driven by a God-ordained unction to manifest greatly in the younger generation. 
        We are here to correct the misconception that proclaims this generation of youth as a wasted one and rebrand the Nigerian youth to
         become worthy ambassadors and reputable leaders.

The right of a youth to learn is our responsibility to uphold. The uniqueness of their enthusiastic minds brings forth a craving to learn, and it is this craving that we satisfy. We harness the depth of talent embedded in the youth and mould the youth for the performance of exploits.</h1>
    </div>
  </div>

    <div class="flex justify-center items-center mt-5">
      <transition appear>
        <img src="https://cdn.dribbble.com/users/515705/screenshots/14103055/media/87a85af61ed42b2e6ca38e233d4b4e9b.jpg?resize=640x480&vertical=center" alt="Rotating image"
        class="w-40 h-40 md:w-96 md:h-96 animate-spin-custom rounded-full "/>
      </transition>
    </div>
  </div>


  <div class="grid grid-cols-1 md:grid-cols-3 mt-5 gap-3 px-4" >
    <div class="min-h-[500px] bg-red-700 rounded-xl px-4 transform transition duration-300 hover:scale-105 flex flex-col justify-center items-center hover:animate-pulse hover:opacity-80 ">
      <i class="bi bi-cash-stack text-7xl text-white"></i>
      <h1 class="text-white text-2xl font-bold">OUR VISION</h1>
    <h1 class='text-white text-xl' >To foster the academic, spiritual, physical, and emotional development of every Child.</h1>
    </div>
    <div class="min-h-[500px] bg-purple-700 rounded-xl px-4 transform transition duration-300 hover:scale-105 flex flex-col justify-center items-center hover:animate-pulse hover:opacity-80 ">
      <i class="bi bi-mortarboard text-white text-7xl "></i>
      <h1 class="text-white text-2xl font-bold">OUR MOTTO</h1>
    <h1 class='text-white text-xl' >Knowledge shines, a beacon bright,      
      Guiding minds through day and night.
      We pave the way, with care and grace,
      For eager hearts to find their place.</h1>
    </div>
    <div class="min-h-[500px] bg-blue-700 rounded-xl px-4 transform transition duration-300 hover:scale-105 flex flex-col justify-center items-center hover:animate-pulse hover:opacity-80 ">
      <i class="bi bi-mortarboard text-white text-7xl "></i>
      <h1 class="text-white text-2xl font-bold">OUR MISSION</h1>
    <h1 class='text-white text-xl' >We lead our students into the future by connecting them with higher institutions locally and internationally 
      with the help of capable and well-informed Admission Officers.
       By doing this, we relieve our parents of the stress of first-degree admission processes within and outside the country.</h1>
    </div>
    
  </div>
      

  <div class="flex flex-col md:flex-row px-6 mt-20">
  <!-- Text Section -->
  <div class="flex flex-col md:w-1/2" data-aos="zoom-in">
    <h1 class="flex justify-center text-blue-700 text-3xl md:text-6xl font-bold">Why Choose Oxbridge Academy?</h1>
    <h2 class="text-lg text-red-400 mt-2">Discover what makes us different...</h2>
    <p class="text-gray-500 text-xl mt-4">
      At The Ambassadors College, Ota, we specialize in nurturing each student for success. Regardless of a learner's
      abilities, talents, and interests, our teaching approaches are geared towards stimulating the minds of all students.
      Our personalized learning approach is tailored to augment what is being taught in classes. This way, we get to know each
      scholar's weaknesses, strengths, and struggles and the appropriate approach to get them back on track.
    </p>
  </div>
  
  <!-- Image Section -->
  <div class="mt-6 md:mt-0 md:w-1/2 flex justify-center items-center">
    <img src="https://cdn.dribbble.com/users/812639/screenshots/16114336/media/220ba3f673e2855eb83d9bc86abbbc08.jpg?resize=640x480&vertical=center" 
         class="w-full h-auto" alt="Oxbridge Academy Image">
  </div>
</div>


<div class="mt-5" >
      <video class="w-full h-[500px] rounded-lg " >
      <source   src="https://cdn.dribbble.com/users/516449/screenshots/14830150/media/9ee0b1df1b61b50d3d57184ba20b5834.mp4" >
    </video>
    </div>
      
    <div data-aos="zoom-in">
   <div cllass="flex flex-col " >
    <h1 class="text-blue-700 px-4 mt-20 font-bold text-3xl flex justify-center">SOME OF OUR VARIOUS PARENTS FEEDBACK</h1>
    <div class="mt-5" >
    <div class="grid grid-cols-1 md:grid-cols-3 gap-5 px-4" >
      <div class='min-h-[300px] shadow-md rounded-xl px-4 py-4 bg-blue-900 ' >
        <h1 class="text-white text-xl" >I am incredibly pleased with the education my child is receiving here. The teachers are not only knowledgeable but genuinely 
          care about the students. My child comes home excited about what they’re learning, which is so important. 
          I appreciate the school's commitment to academic excellence and the focus on preparing students for their future.</h1>
          <div class="flex flex-col mt-3">
          <h1 class=" text-white text-sm flex justify-center">engr ifedolapo</h1>
          <h1 class=" text-gray-300 text-sm flex justify-center">sofware developer (CEO ifedollarsgroups)</h1>
          </div>
      </div>
      <div class='min-h-[300px] shadow-md rounded-xl bg-blue-900  px-4 py-4' >
        <h1 class="text-white text-xl" >
          his school has been a wonderful environment for my child to grow academically and personally.
           The range of subjects offered, along with the support provided by the staff, really gives students a well-rounded education. 
          The school values discipline, respect, and community, which shows in the positive environment they create
        </h1>
        <div class="flex flex-col mt-3">
          <h1 class=" text-white text-sm flex justify-center">mrs modupe folayan</h1>
          <h1 class=" text-gray-300 text-sm flex justify-center">DOCTOR/NURSE</h1>
          </div>
      </div>
      <div class='min-h-[300px] shadow-md rounded-xl bg-blue-900  px-4 py-4' >
        <h1 class="text-white text-xl" >
          As a parent, I’m so grateful for this school. The communication between teachers and parents is excellent,
           and I always feel informed and involved in my child’s education. 
          The school has a real sense of community, and the dedication to student success is clear in everything they do
        </h1>
        <div class="flex flex-col mt-3">
          <h1 class=" text-white text-sm flex justify-center">mr olawale</h1>
          <h1 class=" text-gray-300 text-sm flex justify-center">CIVIL ENGINNER</h1>
          </div>
      </div>
    </div>
    </div>
   </div>
    </div>

    <div id="carouselExampleSlidesOnly" class="carousel slide mt-5" data-bs-ride="carousel" data-bs-interval="1000">
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="https://cdn.dribbble.com/users/4125071/screenshots/18446348/media/920c0fe46d7cb78f0aa8fc646210f2c7.png?resize=640x480&vertical=center"
       class="d-block w-100" alt="">
    </div>
    <div class="carousel-item">
      <img src="https://cdn.dribbble.com/users/730703/screenshots/6609091/lawrenceville_1.jpg?resize=640x480&vertical=center" 
      class="d-block w-100" alt="">
    </div>
    <div class="carousel-item">
      <img src="https://cdn.dribbble.com/userupload/13815827/file/original-6a95e16cd44fd16485edde53ad362fe6.jpg?resize=752x553" 
      class="d-block w-100" alt="">
    </div>
  </div>
</div>

<footer class="bg-gray-900 text-white py-10 px-6 md:px-12">
  <div class="container mx-auto flex flex-col md:flex-row md:justify-between space-y-6 md:space-y-0">
    <!-- Left Column -->
    <div class="flex flex-col space-y-4 md:w-1/2">
      <p class="text-sm">Knowledge is light</p>

      <!-- Address and Contact Info -->
      <p class="text-sm">
        1b, Unity estate borehole, Ota, Ogun State
      </p>
      <p class="text-sm flex items-center">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 10l6-6m0 0l6 6M9 4v16m3-10h8m-8 4h8" />
        </svg>
        +2348055103018, +2348056175107
      </p>
      <p class="text-sm flex items-center">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 10l6-6m0 0l6 6M9 4v16m3-10h8m-8 4h8" />
        </svg>
        taofeeqifedollar@gmail.com
      </p>
      <p class="text-sm flex items-center">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 10l6-6m0 0l6 6M9 4v16m3-10h8m-8 4h8" />
        </svg>
        Mon – Sat open, Sunday closed
      </p>
    </div>

    <!-- Right Column -->
    <div class="flex flex-col md:w-1/2 space-y-4">
      <!-- Working Days and Hours -->
      <div>
        <p class="font-bold text-lg">Working Days:</p>
        <p>Monday – Saturday</p>
      </div>
      <div>
        <p class="font-bold text-lg">Working Hours:</p>
        <p>8:00 AM – 6:00 PM</p>
      </div>

      <!-- Social Media Links -->
      <div>
        <p class="font-bold text-lg">Follow Us</p>
        <div class="flex space-x-4 mt-2">
          <a href="#" class="text-blue-600"><i class="fab fa-facebook-f"></i></a>
          <a href="#" class="text-blue-400"><i class="fab fa-twitter"></i></a>
          <a href="#" class="text-red-500"><i class="fab fa-youtube"></i></a>
          <a href="#" class="text-blue-400"><i class="fab fa-instagram"></i></a>
        </div>
      </div>
    </div>
  </div>

  <!-- Copyright -->
  <div class="bg-blue-800 text-center py-4 mt-6 text-sm">
    Copyright © The oxbridge academy, borehole, Ota 2024.
  </div>

  <!-- Back to Top Button -->
  <button class="fixed bottom-4 right-4 bg-blue-600 text-white p-2 rounded-full shadow-lg" onclick="window.scrollTo({top: 0, behavior: 'smooth'})">
    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 15l7-7 7 7" />
    </svg>
  </button>
</footer>
  </template>
  

<script>
import AOS from 'aos';
import 'aos/dist/aos.css';

export default {
  name: 'RotatingImage',
  data () {
    return {
      menuOpen: false,
    };
  },
  methods: {
    toggleMenu() {
      this.menuOpen = !
      this.menuOpen;
    },
  },
  mounted() {
    AOS.init();
  }
};
</script>

<style>
@keyframes spin {
  from {
    transform: rotate(0deg);
  }
  to {
    transform: rotate(360deg);
  }
}

.animate-spin-custom {
  animation: spin 3s linear infinite;
}

</style>

