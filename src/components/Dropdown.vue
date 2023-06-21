<script setup>
  console.log("aaaa")
</script>

<template>
  <div class="c-dropdown">
    <div class="c-dropdown-input">
      <div class="c-dropdown-label c-dropdown-text-overflow">
        <span>Select a Country</span>
      </div>
      <div class="c-dropdown-trigger">
        <svg
            width="14"
            height="14"
            viewBox="0 0 14 14"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
            class=""
            aria-hidden="true"
        >
          <path
              d="M7.01744 10.398C6.91269 10.3985 6.8089 10.378 6.71215 10.3379C6.61541 10.2977 6.52766 10.2386 6.45405 10.1641L1.13907 4.84913C1.03306 4.69404 0.985221 4.5065 1.00399 4.31958C1.02276 4.13266 1.10693 3.95838 1.24166 3.82747C1.37639 3.69655 1.55301 3.61742 1.74039 3.60402C1.92777 3.59062 2.11386 3.64382 2.26584 3.75424L7.01744 8.47394L11.769 3.75424C11.9189 3.65709 12.097 3.61306 12.2748 3.62921C12.4527 3.64535 12.6199 3.72073 12.7498 3.84328C12.8797 3.96582 12.9647 4.12842 12.9912 4.30502C13.0177 4.48162 12.9841 4.662 12.8958 4.81724L7.58083 10.1322C7.50996 10.2125 7.42344 10.2775 7.32656 10.3232C7.22968 10.3689 7.12449 10.3944 7.01744 10.398Z"
              fill="#676769"
          ></path>
        </svg>
      </div>
    </div>

    <!-- Dropdown panel -->
    <div class="c-dropdown-panel">
      <div class="c-dropdown-header">
        <div class="c-dropdown-search-container">
          <input type="text" class="c-dropdown-search" role="searchbox" autocomplete="off"/>
          <svg xmlns="http://www.w3.org/2000/svg" width="23px" height="23px" viewBox="0 0 24 24" fill="none"
               class="c-dropdown-search-icon">
            <path
                d="M20 20L15.8033 15.8033C15.8033 15.8033 14 18 10.5 18C6.35786 18 3 14.6421 3 10.5C3 6.35786 6.35786 3 10.5 3C14.6421 3 18 6.35786 18 10.5C18 11.0137 17.9484 11.5153 17.85 12"
                stroke="#4D4D4F" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
          </svg>
        </div>
      </div>

      <div class="c-dropdown-items-wrapper">
        <ul class="c-dropdown-items" role="listbox">
          <li class="c-dropdown-item-wrapper" role="option">
            <div class="c-dropdown-item c-dropdown-multiple-item c-dropdown-text-overflow">
              <input type="checkbox" name="" class="c-dropdown-item-checkbox" id="checked-item1">
              <label for="checked-item1"
                     class="c-dropdown-item-checkbox-label c-dropdown-text-overflow">Bangladesh</label>
            </div>

            <div class="c-dropdown-item-icon">
              <svg xmlns="http://www.w3.org/2000/svg" width="28px" height="28px" viewBox="0 0 24 24" fill="none">
                <g id="Interface / Check">
                  <path id="Vector" d="M6 12L10.2426 16.2426L18.727 7.75732" stroke="#F04935" stroke-width="2"
                        stroke-linecap="round" stroke-linejoin="round"/>
                </g>
              </svg>
            </div>
          </li>
          <li class="c-dropdown-item-wrapper" role="option">
            <div class="c-dropdown-item c-dropdown-multiple-item c-dropdown-text-overflow">
              <input type="checkbox" name="" class="c-dropdown-item-checkbox" id="checked-item2">
              <label for="checked-item2"
                     class="c-dropdown-item-checkbox-label c-dropdown-text-overflow">Bangladesh</label>
            </div>

            <div class="c-dropdown-item-icon">
              <svg xmlns="http://www.w3.org/2000/svg" width="28px" height="28px" viewBox="0 0 24 24" fill="none">
                <g id="Interface / Check">
                  <path id="Vector" d="M6 12L10.2426 16.2426L18.727 7.75732" stroke="#F04935" stroke-width="2"
                        stroke-linecap="round" stroke-linejoin="round"/>
                </g>
              </svg>
            </div>
          </li>
          <li class="c-dropdown-item-wrapper" role="option">
            <div class="c-dropdown-item c-dropdown-text-overflow">Australia</div>

            <div class="c-dropdown-item-icon">
              <svg xmlns="http://www.w3.org/2000/svg" width="28px" height="28px" viewBox="0 0 24 24" fill="none">
                <g id="Interface / Check">
                  <path id="Vector" d="M6 12L10.2426 16.2426L18.727 7.75732" stroke="#F04935" stroke-width="2"
                        stroke-linecap="round" stroke-linejoin="round"/>
                </g>
              </svg>
            </div>
          </li>
          <li class="c-dropdown-item-wrapper" role="option">
            <div class="c-dropdown-item c-dropdown-text-overflow">Australia</div>

            <div class="c-dropdown-item-icon">
              <svg xmlns="http://www.w3.org/2000/svg" width="28px" height="28px" viewBox="0 0 24 24" fill="none">
                <g id="Interface / Check">
                  <path id="Vector" d="M6 12L10.2426 16.2426L18.727 7.75732" stroke="#F04935" stroke-width="2"
                        stroke-linecap="round" stroke-linejoin="round"/>
                </g>
              </svg>
            </div>
          </li>
          <li class="c-dropdown-item-wrapper" role="option">
            <div class="c-dropdown-item c-dropdown-multiple-item c-dropdown-text-overflow">
              <span>F3</span> - <span class="c-dropdown-text-overflow">England</span>
            </div>

            <div class="c-dropdown-item-icon">
              <svg xmlns="http://www.w3.org/2000/svg" width="28px" height="28px" viewBox="0 0 24 24" fill="none">
                <g id="Interface / Check">
                  <path id="Vector" d="M6 12L10.2426 16.2426L18.727 7.75732" stroke="#F04935" stroke-width="2"
                        stroke-linecap="round" stroke-linejoin="round"/>
                </g>
              </svg>
            </div>
          </li>
          <li class="c-dropdown-item-wrapper" role="option">
            <div class="c-dropdown-item c-dropdown-multiple-item c-dropdown-text-overflow">
              <span>F3</span> - <span class="c-dropdown-text-overflow">England</span>
            </div>

            <div class="c-dropdown-item-icon">
              <svg xmlns="http://www.w3.org/2000/svg" width="28px" height="28px" viewBox="0 0 24 24" fill="none">
                <g id="Interface / Check">
                  <path id="Vector" d="M6 12L10.2426 16.2426L18.727 7.75732" stroke="#F04935" stroke-width="2"
                        stroke-linecap="round" stroke-linejoin="round"/>
                </g>
              </svg>
            </div>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<style scoped>
li {
  list-style: none;
}

input {
  outline: none;
}

.c-dropdown {
  width: 100%;
  position: relative;
}

.c-dropdown-input {
  display: flex;
  justify-content: space-between;
  background-color: #fff;
  border: 1px solid #DBDBDB;
  border-radius: 4px;
  cursor: pointer;
}

.c-dropdown-text-overflow {
  text-overflow: ellipsis;
  white-space: nowrap;
  overflow: hidden;
}

.c-dropdown-label {
  background-color: transparent;
  padding: 0.75rem 0.625rem;
  font-size: 0.875rem;
  line-height: 1.2;
  color: #151414;
}

.c-dropdown-trigger {
  padding: 0.625rem 0.5rem;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: transparent;
  color: #6c757d;
  width: 3rem;
}

.c-dropdown-panel {
  position: absolute;
  width: 100%;
  z-index: 9;
}

.c-dropdown-header {
  padding: 0.75rem 1.25rem;
  background-color: #f8f9fa;
  color: #151414;
  border-bottom: 1px solid #dee2e6;
  border-top-right-radius: 4px;
  border-top-left-radius: 4px;
}

.c-dropdown-search-container {
  position: relative;
}

.c-dropdown-search {
  width: 100%;
  font-size: 0.875rem;
  padding: 0.75rem 2.5rem 0.75rem 0.75rem;
  background-color: #ffffff;
  color: #151414;
  border: 1px solid #ced4da;
  transition: border-color 0.2s,;
  border-radius: 4px;
}

.c-dropdown-search:focus {
  border-color: #7e7e7e;
}

.c-dropdown-search-icon {
  position: absolute;
  right: 0;
  top: 50%;
  translate: -50% -50%;
}

.c-dropdown-items-wrapper {
  max-height: 270px;
  overflow: hidden;
  overflow-y: auto;
  background-color: #FFFFFF;
  box-shadow: 0px 6px 70px rgba(50, 50, 50, 0.2);
  border-radius: 4px;
  padding: 0.5rem 1rem;
}

.c-dropdown-item-wrapper {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 0.75rem;
  background-color: transparent;
  padding: 0.625rem 0.5rem;
  border-top: 1px dashed #DBDBDB;
  border-radius: 4px;
  color: #151414;
  cursor: pointer;
  font-weight: 400;
  transition: background-color .2s;
}

.c-dropdown-item-wrapper:first-child {
  border-top: none;
}

.c-dropdown-item {
  position: relative;
}

.c-dropdown-multiple-item {
  display: flex;
  align-items: center;
  gap: 12px;
}

.c-dropdown-item-checkbox {
  position: relative;
  border: 2px solid #151414;
  background-color: transparent;
  border-radius: 2px;
  height: 20px;
  min-width: 20px;
  -webkit-appearance: none;
  cursor: pointer;
  opacity: .5;
  transition: border, background-color .3s;
}

.c-dropdown-item-checkbox:hover {
  opacity: 1;
}

.c-dropdown-item-checkbox:checked {
  background-color: #48A43F;
  border-color: #48A43F;
  opacity: 1;
}

.c-dropdown-item-checkbox:before {
  content: '';
  position: absolute;
  width: 4px;
  height: 10px;
  border: solid #fff;
  border-width: 0 2px 2px 0;
  margin: -1px -1px 0 -1px;
  transform: rotate(45deg) translate(-50%, -50%);
  z-index: 2;
  top: 50%;
  right: 50%;
}

.c-dropdown-item-checkbox-label {
  position: relative;
  cursor: pointer;
}

.c-dropdown-item-wrapper .c-dropdown-item-icon {
  opacity: 0;
  transition: opacity .2s;
}

.c-dropdown-item-wrapper:hover .c-dropdown-item-icon {
  opacity: 1;
}

.c-dropdown-items-wrapper::-webkit-scrollbar {
  width: 12px;
  height: 61px;
}

.c-dropdown-items-wrapper::-webkit-scrollbar-track {
  border-radius: 10px;
  border: 1px solid #EDEDED;
}

.c-dropdown-items-wrapper::-webkit-scrollbar-thumb {
  background: #DBDBDB;
  border-radius: 10px;
}

.c-dropdown-items-wrapper::-webkit-scrollbar-thumb:hover {
  background: #bbbbbb;
}


@media only screen and (max-width: 640px) {
  body {
    margin: 1rem;
  }
}
</style>