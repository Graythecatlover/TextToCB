chrome.runtime.getBackgroundPage(function (p) {
    p.chrome.management.setEnabled("PASTE EXTENSION ID TO DISABLE HERE", false);
});
