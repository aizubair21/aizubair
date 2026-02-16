<script lang="ts" setup>

</script>

<template>
  <div class="p-6 space-y-8">
    <!-- Buttons Section -->
    <section>
      <h2 class="text-lg font-semibold mb-4">Buttons</h2>
      <div class="flex gap-4">
        <Button variant="primary">Primary Button</Button>
        <Button variant="secondary">Secondary Button</Button>
      </div>
    </section>

    <!-- Nav Links Section -->
    <section>
      <h2 class="text-lg font-semibold mb-4">Nav Links with Hover Effect</h2>
      <div class="flex gap-6">
        <NavLink href="#">Home</NavLink>
        <NavLink href="#" active>About</NavLink>
        <NavLink href="#">Services</NavLink>
        <NavLink href="#">Contact</NavLink>
      </div>
    </section>

    <!-- Cart Section -->
    <section>
      <h2 class="text-lg font-semibold mb-4">Cart Component</h2>
      <div class="max-w-md">
        <Cart>
          <template #header>
            header
          </template>
          <template #body>
            <Content>This is the cart body content. It demonstrates the content component with gray-500 text and text-sm sizing.</Content>
          </template>
        </Cart>
      </div>
    </section>

    <!-- cart without header or body  -->
     <Cart>
        hellow
        <template #header>
            Title
        </template>
        <template #body> 
            <Content>This is body content without a heading</Content>
        </template>
     </Cart>

    <!-- Typography Section -->
    <section>
      <h2 class="text-lg font-semibold mb-4">Typography Components</h2>
      <div class="space-y-4 max-w-md">
        <Title> asd </Title>
        <Content>This is a content component with gray-500 text and text-sm size.</Content>
        <P>This is a paragraph component with gray-500 text-xs font. It's typically used for smaller text descriptions.</P>
      </div>
    </section>

    <section>
        <CommonHeading heading="This is title" sub-heading="this is content" />
    </section>
  </div>
</template>

<style lang="postcss" scoped>
</style>
