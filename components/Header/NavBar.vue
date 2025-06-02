<script setup lang="ts"></script>

<template>
  <!-- Outer wrapper -->
  <div class="relative mt-3 overflow-hidden">
    <!-- Inner wrapper -->
    <div
      class="relative flex flex-row items-center justify-between w-full h-16 border border-surface-200 bg-surface-0 rounded-md p-4"
    >
      <!-- TODO: Logo area -->
      <h1>DevEsk Job Board</h1>
      <!-- Buttons area -->
      <div class="flex flex-row gap-2 relative w-auto">
        <!-- Login -->
        <!-- <PrimeButton label="Giriş Yap" size="small" variant="outlined" /> -->
        <!-- New job posting -->
        <PrimeButton label="Yeni İlan" size="small">
          <template #icon>
            <PhosphorIconPlusCircle
              weight="fill"
              size="22"
              class="text-surface-0"
            />
          </template>
        </PrimeButton>
      </div>
    </div>
  </div>
</template>
