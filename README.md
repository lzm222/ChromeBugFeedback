# Problem Description

When using the **drag-and-drop** method to select text on a webpage, the entire browser may become unresponsive. The problem resolves when **Windows Search** is opened.

# Reproduction Steps

1. Use Windows Search to search for any content, and drag any resulting link into Chrome (this step may not be necessary).
2. Wait for a few minutes (this step may not be necessary).
3. Select and drag any piece of text on a webpage; the problem will occur.
4. Open the Windows Search window, and Chrome will resume normal operation.

# Trigger Conditions

Arbitrary; **intermittently**.

# Dump File

In the repository, generated via Task Manager.

# System Information

OS Version Windows 10 Chinese Home Edition 
Version Number `22H2`
OS Build `19045.6216`
Chrome Version `132.0.6834.84 (Official Build) (64-bit)`