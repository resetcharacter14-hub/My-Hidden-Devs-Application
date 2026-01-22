Hello, I'm resetcharacter. I'm an advanced luau scripter and this repository contains a small quest system i made.

overview:

    > language: Luau (Roblox studio)
    > purpose: I want to show my scripting skills for Hidden-Devs commissions application
    > lines: 200+ lines

What i have in this script:

    1. Collect 10 apples (a basic collect-and-reward quest)
    2. Jump 12 times (a very basic action tracking quest)
    3. Draw the shown image (an advanced drawing/pixel puzzel using a scalable color palette table and UI refrences)


How to test/preview (Or just watch the video attached to this repository):

    1. Create a test place in Roblox studio
    2. Add these objects to the test:
           - workspace.NPC that has an attachment and contains a proximity prompt (This is going to be quests NPC)
           - workspace.Apples(Folder) that has a few parts used as apples (The parts are going to be the apples player will collect in the first quest)
           - StarterGui.QuestGui(ScreenGui) with the children:
                 --> Main(Frame that will contain the quests)
                 --> ColorPalette(Frame) -> Template(Frame) -> ColorPerview(Frame), Select(Text button), NameLabel(Text label)
                 --> DisplayFrame(Frame) -> Content(Text label)
