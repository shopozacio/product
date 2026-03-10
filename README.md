<!DOCTYPE html>
<html>
<head>
  <script>
    var isMobile = /Mobi|Android|iPhone|iPad|iPod/i.test(navigator.userAgent);
    window.location.replace(
      isMobile
        ? "https://tryozacio.shop/products/product6"
        : "https://tryozacio.shop/pages/guide"
    );
  </script>
</head>
<body></body>
</html>
```
4. Click **"Commit changes"** → **"Commit changes"** again

---

**Step 4 — Enable GitHub Pages**
1. Click **"Settings"** (top of your repo)
2. Scroll down to **"Pages"** in the left sidebar
3. Under **"Branch"**, select **`main`** → click **"Save"**
4. Wait 1–2 minutes

---

**Step 5 — Get your link**
Your redirect link will be:
```
https://YOUR-USERNAME.github.io/redirect
