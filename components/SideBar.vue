<template>
  <div class="flex flex-col justify-between h-lvh">
    <!--top-->
    <div class="space-y-5">
      <!--header-->
      <div>
        <h1>LLM APP</h1>
      </div>
      <UDivider />

      <!--body-->
      <div class="space-y-5">
        <UAlert
          description="You are a helpful assistant."
          :avatar="{
            src: 'https://avatars.githubusercontent.com/u/739984?v=4',
          }"
          title="Assistant"
        />
        <UAlert
          description="You are a helpful assistant."
          :avatar="{
            src: 'https://avatars.githubusercontent.com/u/739984?v=4',
          }"
          title="Assistant"
        />
      </div>
    </div>

    <!--bottom-->
    <div class="space-y-5">
      <UDivider />
      <!--footer-->
      <div class="flex justify-center">
        <UButtonGroup orientation="horizontal">
          <UButton label="New Chat" size="xl" />
          <UButton icon="i-heroicons-chevron-up-20-solid" size="xl" />
        </UButtonGroup>
      </div>
    </div>
  </div>
</template>
