# MordhauCommunityMapInstaller
This application interfaces with a server hosting all approved Community maps, and provides a list for users to pick which maps they would like to download
Maps are downloaded and installed with one click, helping users to avoid confusion finding Mordhau paths to put the maps in

If your Mordhau path cannot be found via registry, you will be prompted to set it by browsing to your Mordhau folder
@D.Mentia on Discord if you have any questions or find any bugs or problems


Important information:
Preview image minimum size: 698, 146
Note that preview images can, and should be, bigger than this - they will be centered and cropped

Info file format:
Filename: FolderName.info.txt
Each of these parameters on newlines, in order

MapName (Can include spaces, readable name for display purposes only)
FolderName (Specific name of the zip file and folder and in-game mapname)
MapDescription (Can include links that will be clickable)
MapAuthor(s)
MapVersion
ReleaseDate (In format: dd/mm/yyyy)
FileSize (Unzipped size of all files)
Optional: MaxPlayers (Set low for small maps)
Optional: Thumbnail URL
