## Injecting messages

- Now scroll back up to the list of nodes. To turn the LED on and off, we need an input. In Node-RED we can inject messages into the flow and cause things to happen as a result. Drag an **inject** node onto the flow.

 ![Inject node](images/inject-node.png)

- Double-click on the inject node. Use the drop down next to **Payload** to change the data type to **string** and type `1` in the Payload box - this will be the message. Type `On` in the **Name** box. Press Done.

 ![Edit inject node](images/edit-inject.png)

- Repeat the previous steps to create another inject node, except this time add `0` as the payload message, and call this node **Off**.

 ![Create two inject nodes](images/add-2-nodes.png)

- Now look for the grey dot on the right side of the inject nodes. Click and drag from the grey dot on the **On** node to the grey dot on your LED node to join them up. Repeat for the **Off** node, also joining it to the LED node.

 ![Join nodes together](images/join-nodes.png)

