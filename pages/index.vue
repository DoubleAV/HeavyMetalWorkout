<template>
  <div class="container mx-auto">
    <ul>
      <li v-for="exercise in exercises" :key="exercise.name">
        {{ exercise.name }}
      </li>
    </ul>
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
