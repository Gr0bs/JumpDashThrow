<template>
  <div class="container mx-auto">
    <header class="text-center">
      <h2>Retrouvez tous les tournois online/offline de vos jeux de versus !</h2>
      <img class="w-min mx-auto" src="https://picsum.photos/300/300" alt="Logo Home">
    </header>

    <!-- LAST TOURNAMENT CAROUSEL -->
    <div class="mt-10">
      <h3 class="text-center my-4 text-2xl ">Prochains tounois</h3>
      <Carousel :list="list" />
    </div>

    <!-- BLABLA DESCRIPTION -->
    <div class="mt-20">
      <h2 class="text-center text-4xl my-14">Qu'est-ce que <strong> Jump Dash Throw </strong> ?</h2>
      <p>
        Bonbon lollipop halvah tootsie roll sugar plum fruitcake tart liquorice bear claw. Topping liquorice jelly beans pastry tiramisu croissant powder sweet roll chocolate. Brownie donut croissant liquorice liquorice pie marzipan ice cream. Brownie wafer oat cake marzipan danish tiramisu topping cake fruitcake. Halvah dragée gummies jujubes tiramisu dessert caramels danish. Oat cake gingerbread sweet ice cream marzipan ice cream. Ice cream wafer powder wafer halvah shortbread. Candy chocolate gummies fruitcake dragée. Jujubes jelly beans apple pie sweet roll croissant. Sweet roll oat cake soufflé powder brownie macaroon pastry bear claw. Macaroon danish pie pastry ice cream cake fruitcake tiramisu toffee. Tootsie roll jelly beans topping chocolate powder jelly. Toffee lollipop cotton candy bonbon sugar plum marshmallow cake soufflé oat cake.
      </p>

      <p class="py-6">
        Halvah dragée gummies jujubes tiramisu dessert caramels danish. Oat cake gingerbread sweet ice cream marzipan ice cream. Ice cream wafer powder wafer halvah shortbread. Candy chocolate gummies fruitcake dragée. Jujubes jelly beans apple pie sweet roll croissant. Sweet roll oat cake soufflé powder brownie macaroon pastry bear claw. Macaroon danish pie pastry ice cream cake fruitcake tiramisu toffee. Tootsie roll jelly beans topping chocolate powder jelly. Toffee lollipop cotton candy bonbon sugar plum marshmallow cake soufflé oat cake.
      </p>
    </div>
  </div>
</template>

<script>
export default {
  data(){
    return {
      list: [
        {name: "From human to God #1", img: "https://picsum.photos/600/800", date: "10/04"},
        {name: "From human to God #1", img: "https://picsum.photos/600/800", date: "10/04"},
        {name: "From human to God #1", img: "https://picsum.photos/600/800", date: "10/04"},
        {name: "From human to God #1", img: "https://picsum.photos/600/800", date: "10/04"},
        {name: "From human to God #1", img: "https://picsum.photos/600/800", date: "10/04"},
        {name: "From human to God #1", img: "https://picsum.photos/600/800", date: "10/04"},
        {name: "From human to God #1", img: "https://picsum.photos/600/800", date: "10/04"},
        {name: "From human to God #1", img: "https://picsum.photos/600/800", date: "10/04"},
        {name: "From human to God #1", img: "https://picsum.photos/600/800", date: "10/04"},
        {name: "From human to God #1", img: "https://picsum.photos/600/800", date: "10/04"},
        {name: "From human to God #1", img: "https://picsum.photos/600/800", date: "10/04"},
        {name: "From human to God #1", img: "https://picsum.photos/600/800", date: "10/04"},
      ]
    }
  }
}
</script>
