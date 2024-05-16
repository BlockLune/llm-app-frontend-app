<template>
  <div class="space-y-2">
    <!--bar-->
    <div class="flex flex-row justify-between">
      <div class="flex flex-row gap-2">
        <UButton icon="i-mingcute-brain-line" color="gray" />
        <UButton icon="i-mingcute-thermometer-line" color="gray" />
        <UButton icon="i-mingcute-pic-line" color="gray" />
        <UButton icon="i-mingcute-mic-line" color="gray" />
      </div>
      <div class="flex flex-row gap-2">
        <UButton icon="i-mingcute-eraser-line" color="gray" />
      </div>
    </div>
    <!--text area-->
    <div>
      <UTextarea
        placeholder="Type your message here ..."
        variant="none"
        :padded="false"
      />
    </div>
    <!--send button-->
    <div class="flex flex-row justify-end">
      <UButtonGroup orientation="horizontal">
        <UButton label="Send" />
        <UButton icon="i-heroicons-chevron-down-20-solid" />
      </UButtonGroup>
    </div>
  </div>
</template>
