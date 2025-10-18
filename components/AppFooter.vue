<template>
  <footer class="reverse-color-mode relative z-20">
    <UContainer>
      <div class="flex items-center justify-between py-10 text-xs">
        <div>
          <p class="text-gray-400 dark:text-gray-500">
            &copy; 2024 forwwward.solutions - MIT License.
          </p>
        </div>
        <div class="flex space-x-4">
          <UTooltip text="forwwward.solutions">
            <ULink
              external
              to="https://www.forwwward.solutions"
              title="forwwward.solutions"
              target="_blank"
            >
              <span class="sr-only">forwwward.solutions</span>
              <UAvatar
                src="https://www.forwwward.solutions/apple-icon-60x60.png"
                alt="Avatar"
              />
            </ULink>
          </UTooltip>
        </div>
      </div>
    </UContainer>
  </footer>
</template>
