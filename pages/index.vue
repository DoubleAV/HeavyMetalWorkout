<template>
  <!-- component -->

  <div class="h-screen w-screen flex bg-gray-900">
    <!-- container -->

    <aside
      class="hidden lg:flex flex-col items-center bg-gray-200 text-gray-700 shadow h-full"
    >
      <!-- Side Nav Bar-->

      <div class="h-16 flex items-center w-full">
        <!-- Logo Section -->
        <a class="h-6 w-6 mx-auto" href="">
          <img class="h-6 w-6 mx-auto" src="/FirstHMLogo.png" alt="logo" />
        </a>
      </div>

      <ul>
        <!-- Items Section -->

        <!-- HomePage/Summary -->
        <li class="hover:bg-gray-100">
          <a
            href="."
            class="h-16 px-6 flex justify-center items-center w-full focus:text-red-600"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="icon icon-tabler icon-tabler-home"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              stroke-width="2"
              stroke="currentColor"
              fill="none"
              stroke-linecap="round"
              stroke-linejoin="round"
            >
              <path stroke="none" d="M0 0h24v24H0z" />
              <polyline points="5 12 3 12 12 3 21 12 19 12" />
              <path d="M5 12v7a2 2 0 0 0 2 2h10a2 2 0 0 0 2 -2v-7" />
              <path d="M9 21v-6a2 2 0 0 1 2 -2h2a2 2 0 0 1 2 2v6" />
            </svg>
          </a>
        </li>

        <!-- Exercise -->
        <li class="hover:bg-gray-100">
          <a
            href="."
            class="h-16 px-6 flex justify-center items-center w-full
					focus:text-orange-500"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="icon icon-tabler icon-tabler-activity"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              stroke-width="2"
              stroke="currentColor"
              fill="none"
              stroke-linecap="round"
              stroke-linejoin="round"
            >
              <path stroke="none" d="M0 0h24v24H0z" />
              <polyline points="21 12 17 12 14 20 10 4 7 12 3 12" />
            </svg>
          </a>
        </li>

        <!-- Tools -->
        <li class="hover:bg-gray-100">
          <a
            href="."
            class="h-16 px-6 flex justify-center items-center w-full
					focus:text-orange-500"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="icon icon-tabler icon-tabler-tools"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              stroke-width="2"
              stroke="currentColor"
              fill="none"
              stroke-linecap="round"
              stroke-linejoin="round"
            >
              <path stroke="none" d="M0 0h24v24H0z" />
              <path d="M3 21h4l13 -13a1.5 1.5 0 0 0 -4 -4l-13 13v4" />
              <line x1="14.5" y1="5.5" x2="18.5" y2="9.5" />
              <polyline points="12 8 7 3 3 7 8 12" />
              <line x1="7" y1="8" x2="5.5" y2="9.5" />
              <polyline points="16 12 21 17 17 21 12 16" />
              <line x1="16" y1="17" x2="14.5" y2="18.5" />
            </svg>
          </a>
        </li>
      </ul>

      <div class="mt-auto h-16 flex items-center w-full">
        <!-- Action Section -->
        <button
          class="h-16 w-10 mx-auto flex justify-center items-center
				w-full focus:text-orange-500 hover:bg-red-200 focus:outline-none"
        >
          <svg
            class="h-5 w-5 text-red-700"
            xmlns="http://www.w3.org/2000/svg"
            width="24"
            height="24"
            viewBox="0 0 24 24"
            fill="none"
            stroke="currentColor"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
          >
            <path d="M9 21H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h4"></path>
            <polyline points="16 17 21 12 16 7"></polyline>
            <line x1="21" y1="12" x2="9" y2="12"></line>
          </svg>
        </button>
      </div>
    </aside>

    <div class="flex-1 flex flex-col">
      <nav class="px-4 flex justify-between bg-gray-200 h-16 border-b-2">
        <!-- top bar -->

        <ul class="flex items-center lg:hidden">
          <!-- top bar left -->
          <li class="h-6 w-6">
            <img
              class="h-full w-full mx-auto"
              src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1b/Svelte_Logo.svg/512px-Svelte_Logo.svg.png"
              alt="svelte logo"
            />
          </li>
        </ul>

        <ul class="flex items-center">
          <!-- top bar center -->
          <li>
            <h1 class="pl-10 lg:pl-0 text-gray-700">Heavy Metal Workout</h1>
          </li>
        </ul>

        <ul class="flex items-center">
          <!-- to bar right  -->

          <li class="h-8 w-8">
            <img
              class="h-full w-full rounded-full mx-auto"
              src="https://images.unsplash.com/photo-1494790108377-be9c29b29330?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&q=60"
              alt="profile woman"
            />
          </li>
        </ul>
      </nav>
    </div>

    <nav
      class="fixed bottom-0 w-full border bg-gray-300 lg:hidden flex
		overflow-x-auto"
    >
      <!-- Bottom Icon Navigation Menu -->

      <!-- Home/Summary -->
      <a
        href="."
        class="flex flex-col flex-grow items-center justify-center
			overflow-hidden whitespace-no-wrap text-sm transition-colors
			duration-100 ease-in-out hover:bg-gray-200 focus:text-red-600"
      >
        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="icon icon-tabler icon-tabler-home"
          width="24"
          height="24"
          viewBox="0 0 24 24"
          stroke-width="2"
          stroke="currentColor"
          fill="none"
          stroke-linecap="round"
          stroke-linejoin="round"
        >
          <path stroke="none" d="M0 0h24v24H0z" />
          <polyline points="5 12 3 12 12 3 21 12 19 12" />
          <path d="M5 12v7a2 2 0 0 0 2 2h10a2 2 0 0 0 2 -2v-7" />
          <path d="M9 21v-6a2 2 0 0 1 2 -2h2a2 2 0 0 1 2 2v6" />
        </svg>

        <span class="text-sm capitalize">Summary</span>
      </a>

      <!-- Exercise -->
      <a
        href="."
        class="flex flex-col flex-grow items-center justify-center
			overflow-hidden whitespace-no-wrap text-sm transition-colors
			duration-100 ease-in-out hover:bg-gray-200 text-red-600"
      >
        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="icon icon-tabler icon-tabler-activity"
          width="24"
          height="24"
          viewBox="0 0 24 24"
          stroke-width="2"
          stroke="currentColor"
          fill="none"
          stroke-linecap="round"
          stroke-linejoin="round"
        >
          <path stroke="none" d="M0 0h24v24H0z" />
          <polyline points="21 12 17 12 14 20 10 4 7 12 3 12" />
        </svg>

        <span class="text-sm capitalize">exercise</span>
      </a>

      <!-- Tools -->
      <a
        href="."
        class="flex flex-col flex-grow items-center justify-center
			overflow-hidden whitespace-no-wrap text-sm transition-colors
			duration-100 ease-in-out hover:bg-gray-200 focus:text-red-600"
      >
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="24"
          height="24"
          viewBox="0 0 24 24"
          fill="none"
          stroke="currentColor"
          stroke-width="2"
          stroke-linecap="round"
          stroke-linejoin="round"
          class="feather feather-bookmark"
        >
          <path d="M19 21l-7-5-7 5V5a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2z"></path>
        </svg>

        <span class="text-sm capitalize">Tools</span>
      </a>

      <!-- Settings section will probably come later -->
      <!-- <a
        href="."
        class="flex flex-col flex-grow items-center justify-center
			overflow-hidden whitespace-no-wrap text-sm transition-colors
			duration-100 ease-in-out hover:bg-gray-200 focus:text-orange-500"
      >
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="24"
          height="24"
          viewBox="0 0 24 24"
          fill="none"
          stroke="currentColor"
          stroke-width="2"
          stroke-linecap="round"
          stroke-linejoin="round"
        >
          <circle cx="12" cy="12" r="3"></circle>
          <path
            d="M19.4 15a1.65 1.65 0 0 0 .33 1.82l.06.06a2 2 0 0 1 0 2.83
					2 2 0 0 1-2.83 0l-.06-.06a1.65 1.65 0 0 0-1.82-.33 1.65 1.65
					0 0 0-1 1.51V21a2 2 0 0 1-2 2 2 2 0 0 1-2-2v-.09A1.65 1.65 0
					0 0 9 19.4a1.65 1.65 0 0 0-1.82.33l-.06.06a2 2 0 0 1-2.83 0 2
					2 0 0 1 0-2.83l.06-.06a1.65 1.65 0 0 0 .33-1.82 1.65 1.65 0 0
					0-1.51-1H3a2 2 0 0 1-2-2 2 2 0 0 1 2-2h.09A1.65 1.65 0 0 0
					4.6 9a1.65 1.65 0 0 0-.33-1.82l-.06-.06a2 2 0 0 1 0-2.83 2 2
					0 0 1 2.83 0l.06.06a1.65 1.65 0 0 0 1.82.33H9a1.65 1.65 0 0 0
					1-1.51V3a2 2 0 0 1 2-2 2 2 0 0 1 2 2v.09a1.65 1.65 0 0 0 1
					1.51 1.65 1.65 0 0 0 1.82-.33l.06-.06a2 2 0 0 1 2.83 0 2 2 0
					0 1 0 2.83l-.06.06a1.65 1.65 0 0 0-.33 1.82V9a1.65 1.65 0 0 0
					1.51 1H21a2 2 0 0 1 2 2 2 2 0 0 1-2 2h-.09a1.65 1.65 0 0
					0-1.51 1z"
          ></path>
        </svg>

        <span class="text-sm capitalize">Settings</span>
      </a> -->
    </nav>
    <!-- <div class="container mx-auto">
      <ul>
        <li v-for="exercise in exercises" :key="exercise.name">
          {{ exercise.name }}
        </li>
      </ul>
    </div> -->
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: '',
      exercises: [
        { name: 'Flat Bench Press' },
        { name: 'Incline Bench Press' },
        { name: 'Decline Bench Press' },
        { name: 'Close-grip Bench Press' },
        { name: 'Reverse-grip Bench Press' },
        { name: 'Close-grip Incline Bench Press' },
        { name: 'Back Squat' },
        { name: 'Front Squat' },
        { name: 'Sumo Squat' },
        { name: 'Goblet Squat' },
        { name: 'Sumo Squat' },
        { name: 'Deadlift' },
        { name: 'Sumo Deadlift' },
        { name: 'Lateral Raise' },
        { name: 'Standing Overhead Press' },
        { name: 'Seated Overhead Press' },
        { name: 'Shoulder Press' },
        { name: 'Seated Shoulder Press' },
        { name: 'Front Raise' },
        { name: 'Rear Delt Fly' },
        { name: 'Chest Fly' },
        { name: 'Shoulder Shrug' },
        { name: 'Standing Biceps Curl' },
        { name: 'Seated Biceps Curl' },
        { name: 'Standing Hammer Curl' },
        { name: 'Seated Hammer Curl' },
        { name: 'Preacher Curl' },
        { name: 'Dips' },
        { name: 'Bench Dips' },
        { name: 'Pull-ups' },
        { name: 'Chin-Ups' },
        { name: 'Skullcrushers' },
        { name: 'Overhead Tricep Extension' },
        { name: 'Tricep Pushdown' },
        { name: 'Bent-Over Row' },
        { name: 'Reverse-Grip Bent-Over Row' },
        { name: 'One-Arm Row' },
        { name: 'Push-Ups' }
      ]
    }
  }
}
</script>
