<h1>Online Notepad</h1>
 <p>Create a notepad as shown in the picture. </p>
 <p>Save My Notes is a feature-flag used to turn on/off the autosave feature. </p>
 <ul>
  <li>When on, the text inside the textarea is stored or updated in the local storage of the browser every 1 sec. 
  </li>
  <li>When off, the local storage is no longer updated & contain only previously saved content.
  </li>
 </ul>
 <p>Note: </p>
 <p>1. On opening the app the Save My Notes checkbox is unchecked.</p>
 <p>2. The key in the local storage should be 'autosave-data'. </p>
 <p>3. The textarea should contain placeholder 'Write your notes here'.</p>
 <h3>Acceptance Criteria</h3>
 <ul>
  <li>All the components should be present with their correct id & value. </li>
  <li>Autosave should only work when the feature-flag is turned on. </li>
  <li>On closing the app & then reopening it, the textarea should contain previously saved content. </li>
 </ul>
