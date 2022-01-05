// UI

var tooltipTriggerList = [].slice.call(document.querySelectorAll('[data-bs-toggle="tooltip"]'))
var tooltipList = tooltipTriggerList.map(function (tooltipTriggerEl) {
  return new bootstrap.Tooltip(tooltipTriggerEl)
})


// START FOOTER
const getyear = document.getElementById('getyear');
const getfullyear = new Date().getFullYear();

getyear.innerHTML = getfullyear;

// END FOOTER