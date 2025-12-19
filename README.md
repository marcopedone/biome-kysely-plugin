# biome-kysely-plugin
Biome plugin for Kysely query builder

# Just add the rules as plugins in Biome configs:
biome.json
```
{

"plugins": ["missing.grit", "null.grit"],
...rest of Biome configs

}
```

## Examples

# selectFrom missing select() or selectAll()
<img width="750" height="133" alt="image" src="https://github.com/user-attachments/assets/f048a04b-c52b-4643-adf1-d65d8ff58df9" />

# updateFrom and deleteFrom missing where()
<img width="676" height="102" alt="image" src="https://github.com/user-attachments/assets/25d119c4-fb25-4554-899a-37f642d6a40d" />

# comparisons to nullable values must use 'is' or 'is not' 
<img width="1257" height="117" alt="image" src="https://github.com/user-attachments/assets/9c46081e-7cc0-4590-b002-6456774129e8" />

