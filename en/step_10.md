## Debugging your flow

- If your LED doesn't turn on and off, firstly check that you have wired the components correctly on the breadboard. Make sure you have wired your LED to both **ground** and **pin 17** on your Raspberry Pi.

 You can also ask Node-RED to display debugging information by wiring up your nodes to a **Debug** node, which can be found under **output**. Drag in a debug node and wire your two inject nodes to it, then click Deploy. When you click the buttons to inject the message, Node-RED will show you what was injected in the **Debug** tab on the right side of the screen. Click the tab to display the messages.

 ![Debug node](images/debug-node.png)

 For example, this is the output if you click first on the **On** node and then on the **Off** node.

 ![Debug panel](images/debug-panel.png)

