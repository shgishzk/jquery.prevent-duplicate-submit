# jquery.prevent-duplicate-submit

## Usage
Call 'disableDuplicateSubmit' method on form to prevent to be duplicate submitted.
```
$('form').disableDuplicateSubmit();
```

Add 'prevent' class to submit button.
```
<button type='submit' class='prevent'>Submit</button>
```

## Notice
Submit button should be in the same context with form.

For example, this case doesn't work.
```
<div>
  <form> <-- This should be placed BEFORE div tag
  <button type="submit" class="prevent">Button</button>
</div>
</form>
```