<script setup lang="ts">
import MainLayout from '@/layouts/MainLayout.vue'
import AboutComponent from '@/components/AboutUs/AboutContent.vue'
import JoinTeam from '@/components/JoinTeam.vue';
</script>

<template>
  <MainLayout>
    <AboutComponent/>
    <!-- Section Article-->
    <section class="px-20 py-24 text-center max-md:px-5">
    <h3 class="text-3xl font-bold text-gray-900">List of Authors</h3>
    <div class="grid grid-cols-4 gap-8 mt-12 max-md:grid-cols-1">
        <!-- Author 1 -->
        <div class="p-8 bg-gray-100 rounded-lg shadow">
            <a href="/author">
                <img class="w-20 h-20 mx-auto rounded-full" src="@/assets/images/misc/home/floyd.png" alt="Floyd Miles" />
            </a>
            <h4 class="mt-4 text-xl font-semibold text-gray-900">
                <a href="/author">Floyd Miles</a>
            </h4>
            <p class="text-sm text-gray-500">Content Writer @Company</p>
            <div class="flex justify-center mt-4 space-x-4 text-gray-500">
                <a href="/author"><i class="fab fa-facebook-f"></i></a>
                <a href="/author"><i class="fab fa-twitter"></i></a>
                <a href="/author"><i class="fab fa-instagram"></i></a>
                <a href="/author"><i class="fab fa-linkedin-in"></i></a>
            </div>
        </div>
        
        <!-- Author 2 -->
        <div class="p-8 bg-gray-100 rounded-lg shadow">
            <a href="/author">
                <img class="w-20 h-20 mx-auto rounded-full" src="@/assets/images/misc/home/dianne.png" alt="Dianne Russell" />
            </a>
            <h4 class="mt-4 text-xl font-semibold text-gray-900">
                <a href="/author">Dianne Russell</a>
            </h4>
            <p class="text-sm text-gray-500">Content Writer @Company</p>
            <div class="flex justify-center mt-4 space-x-4 text-gray-500">
                <a href="/author"><i class="fab fa-facebook-f"></i></a>
                <a href="/author"><i class="fab fa-twitter"></i></a>
                <a href="/author"><i class="fab fa-instagram"></i></a>
                <a href="/author"><i class="fab fa-linkedin-in"></i></a>
            </div>
        </div>
        
        <!-- Author 3 -->
        <div class="p-8 bg-gray-100 rounded-lg shadow">
            <a href="/author">
                <img class="w-20 h-20 mx-auto rounded-full" src="@/assets/images/misc/home/jenny.png" alt="Jenny Wilson" />
            </a>
            <h4 class="mt-4 text-xl font-semibold text-gray-900">
                <a href="/author">Jenny Wilson</a>
            </h4>
            <p class="text-sm text-gray-500">Content Writer @Company</p>
            <div class="flex justify-center mt-4 space-x-4 text-gray-500">
                <a href="/author"><i class="fab fa-facebook-f"></i></a>
                <a href="/author"><i class="fab fa-twitter"></i></a>
                <a href="/author"><i class="fab fa-instagram"></i></a>
                <a href="/author"><i class="fab fa-linkedin-in"></i></a>
            </div>
        </div>
        
        <!-- Author 4 -->
        <div class="p-8 bg-gray-100 rounded-lg shadow">
            <a href="/author">
                <img class="w-20 h-20 mx-auto rounded-full" src="@/assets/images/misc/home/leslie.png" alt="Leslie Alexander" />
            </a>
            <h4 class="mt-4 text-xl font-semibold text-gray-900">
                <a href="/author">Leslie Alexander</a>
            </h4>
            <p class="text-sm text-gray-500">Content Writer @Company</p>
            <div class="flex justify-center mt-4 space-x-4 text-gray-500">
                <a href="/author"><i class="fab fa-facebook-f"></i></a>
                <a href="/author"><i class="fab fa-twitter"></i></a>
                <a href="/author"><i class="fab fa-instagram"></i></a>
                <a href="/author"><i class="fab fa-linkedin-in"></i></a>
            </div>
        </div>
        
        <!-- Author 5 -->
        <div class="p-8 bg-gray-100 rounded-lg shadow">
            <a href="/cauthor">
                <img class="w-20 h-20 mx-auto rounded-full" src="@/assets/images/misc/home/guy.png" alt="Guy Hawkins" />
            </a>
            <h4 class="mt-4 text-xl font-semibold text-gray-900">
                <a href="/author">Guy Hawkins</a>
            </h4>
            <p class="text-sm text-gray-500">Content Writer @Company</p>
            <div class="flex justify-center mt-4 space-x-4 text-gray-500">
                <a href="/author"><i class="fab fa-facebook-f"></i></a>
                <a href="/author"><i class="fab fa-twitter"></i></a>
                <a href="/author"><i class="fab fa-instagram"></i></a>
                <a href="/author"><i class="fab fa-linkedin-in"></i></a>
            </div>
        </div>
        
        <!-- Author 6 -->
        <div class="p-8 bg-gray-100 rounded-lg shadow">
            <a href="/author">
                <img class="w-20 h-20 mx-auto rounded-full" src="@/assets/images/misc/home/eleanor.png" alt="Eleanor Pena" />
            </a>
            <h4 class="mt-4 text-xl font-semibold text-gray-900">
                <a href="/author">Eleanor Pena</a>
            </h4>
            <p class="text-sm text-gray-500">Content Writer @Company</p>
            <div class="flex justify-center mt-4 space-x-4 text-gray-500">
                <a href="/author"><i class="fab fa-facebook-f"></i></a>
                <a href="/author"><i class="fab fa-twitter"></i></a>
                <a href="/author"><i class="fab fa-instagram"></i></a>
                <a href="/author"><i class="fab fa-linkedin-in"></i></a>
            </div>
        </div>
        
        <!-- Author 7 -->
        <div class="p-8 bg-gray-100 rounded-lg shadow">
            <a href="/author">
                <img class="w-20 h-20 mx-auto rounded-full" src="@/assets/images/misc/home/robert.png" alt="Robert Fox" />
            </a>
            <h4 class="mt-4 text-xl font-semibold text-gray-900">
                <a href="/author">Robert Fox</a>
            </h4>
            <p class="text-sm text-gray-500">Content Writer @Company</p>
            <div class="flex justify-center mt-4 space-x-4 text-gray-500">
                <a href="/author"><i class="fab fa-facebook-f"></i></a>
                <a href="/author"><i class="fab fa-twitter"></i></a>
                <a href="/author"><i class="fab fa-instagram"></i></a>
                <a href="/author"><i class="fab fa-linkedin-in"></i></a>
            </div>
        </div>
        
        <!-- Author 8 -->
        <div class="p-8 bg-gray-100 rounded-lg shadow">
            <a href="/author">
                <img class="w-20 h-20 mx-auto rounded-full" src="@/assets/images/misc/home/jacob.png" alt="Jacob Jones" />
            </a>
            <h4 class="mt-4 text-xl font-semibold text-gray-900">
                <a href="/author">Jacob Jones</a>
            </h4>
            <p class="text-sm text-gray-500">Content Writer @Company</p>
            <div class="flex justify-center mt-4 space-x-4 text-gray-500">
                <a href="/author"><i class="fab fa-facebook-f"></i></a>
                <a href="/author"><i class="fab fa-twitter"></i></a>
                <a href="/author"><i class="fab fa-instagram"></i></a>
                <a href="/author"><i class="fab fa-linkedin-in"></i></a>
            </div>
        </div>
    </div>
    <div><JoinTeam/></div>
</section>
  </MainLayout>
</template>
