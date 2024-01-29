# Custom item for activate the Twilight Forest portal (CITATTFP)

<details>
<summary>[EN] Guide for replace item for activate TF portal</summary>

- Open the archive and follow the path: "`data/twilightforest/tags/items/portal`".
- Open the file "`activator.json`".
- Find the line `"id":"divinerpg:hellstone_ingot"`. `"divinerpg:hellstone_ingot"` - is the very item that will replace the diamond.
  - In order to get the item ID, you need to press the key combination **F3 + H** in the Minecraft window, then go to the inventory menu and hover over the item that you want to use instead of the diamond to activate the portal to the TF.
  </br>![](https://cdn.discordapp.com/attachments/1014200166473023540/1061988799753756682/2023-01-09_18.20.4467.png)</br>
  What is highlighted in the photo with a red frame is the ID of the item that needs to be used in `activator.json`. **The ID must be written in the file together with quotes, as shown in the example.**
- After changing the ID, save the file and close the archive.
- Move the archive to the `datapacks` folder located in `C:\Users\(UserName)\AppData\Roaming\.minecraft\saves\(WorldName)\datapacks` for the world you need.
- Everything

</details>

<details>
<summary>[RU] Гайд по замене предмета, активирующего портал в Сумеречный лес</summary>

- Откройте архив и пройдите по пути: "`data/twilightforest/tags/items/portal`".
- Откройте файл "`activator.json`".
- Найдите строку `"id":"divinerpg:hellstone_ingot"`. `"divinerpg:hellstone_ingot"` - является тем самым предметом, который будет заменять собой алмаз. 
  - Для того чтобы получить ID предмета, нужно нажать комбинацию клавиш **F3 + H** в окне Minecraft, после перейти в меню инвентаря и навестись курсором на предмет, который вы хотите использовать заместо алмаза, для активации портала в СЛ.
  </br>![](https://cdn.discordapp.com/attachments/1014200166473023540/1061988799753756682/2023-01-09_18.20.4467.png)</br>
  То, что выделено на фото красной рамкой и является ID предмета, который нужно использовать в `activator.json`. **Записывать ID в файле нужно вместе с кавычками, как показано в примере.**
- После смены идентификатора сохраните файл и закройте архив.
- Переместите архив в папку `datapacks` находящиеся в `C:\Users\(UserName)\AppData\Roaming\.minecraft\saves\(WorldName)\datapacks` для нужного вам мира.
- Всё

</details>

---

<details>
<summary>Examples activator.json code:</summary>

<details>
<summary>Diamond to sniffer egg:</summary>

```json
{
  "replace": true,
  "values": [
    {
      "id":"minecraft:sniffer_egg",
      "required":false
    }
  ]
}
```

</details>

<details>
<summary>Diamond to totem of undying:</summary>

```json
{
  "replace": true,
  "values": [
    {
      "id":"minecraft:totem_of_undying",
      "required":false
    }
  ]
}
```

</details>

<details>
<summary>Diamond to trident:</summary>

```json
{
  "replace": true,
  "values": [
    {
      "id":"minecraft:trident",
      "required":false
    }
  ]
}
```

</details>

</details>
