<script>
    let cities = [
      {
        id: "3287",
        name: "London"
      },
      {
        id: "3914",
        name: "Warsaw"
      },
      {
        id: "8833",
        name: "Berlin"
      },
      {
        id: "3231",
        name: "Lisbon"
      }
    ];
  </script>
  
  <h1>European cities:</h1>
  <ul>
    {#each cities as { id, name }, index}
      <li>{index + 1}: {name} (id: {id})</li>
    {/each}
  </ul>