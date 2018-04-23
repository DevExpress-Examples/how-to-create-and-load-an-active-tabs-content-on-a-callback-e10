# How to create and load an active tab's content on a callback


<p>This sample demonstrates how to create and load an active tab's content on a callback. This allows you to reduce Page_Load time on the server, because content hierarchy won't be created for invisible pages.</p><p>Please note that the technique demonstrated in the sample is viable only when displaying static content on a tab page - the content that is state-independent (i.e. not connected with ViewState, ControlState, CallbackState, or any other state). Examples of such a content include: text documents, messages, etc.</p>

<br/>

