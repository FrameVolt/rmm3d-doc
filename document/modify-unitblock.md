# 3️⃣ Modify UnitBlock



### Modify UnitBlock:

* Before modifying, make sure you have created UnitBlockTreeAsset.(You can create it by right click in the project panel "Create/RMM3D/TreeAssets/UnitBlock Tree Asset")

<img src="../.gitbook/assets/image (16).png" alt="" data-size="original">

* At "Modifty unitBlock" tab. You can see the UnitBlockTreeAsset you created, And drag and drop your converted unitBlock prefab(converted from sourcePrefab) to the treeview box on the left.

![](<../.gitbook/assets/image (3).png>)

* In order for your unit blocks to be selected in the blocks selection panel, you need to create a preview image for them.

![](<../.gitbook/assets/image (17).png>)

* RMM3D provides you with a simple solution, you can click the "Generate preview textures" button on the "Modify unitBlock" Tab to generate simple previews. By default, these generated images will be at ("Assets/RuntimeMapMaker3D/ArtWorks/Textures/UnitBlocksIcon/"), you can also change the output directory in the settings tab. Of course, it should be noted that these preview images also need to be packaged into assetbundle like simple start up does.

![](<../.gitbook/assets/image (7).png>)

* After generated preview images, We need to generate data model for unitblocks and bind them to RMM3D. Click the following 3 buttons "Add to MakerSceneSetting", "Create UnitBlockModels", "Add unitBlock facade component".

![](<../.gitbook/assets/image (14).png>)

* Build Asset bundle, at "modify unitBlock" tab.

![](<../.gitbook/assets/image (11).png>)

* Now, you can start the journey of RMM3D.
