<template>
<div class="userprofile">
  <div class="container">
    <div class="columns">
      <div class="md-col-4 md-pr-0 md-pl-0">
        <div class="profilecard">
          <div class="profilecard-desc">
            <div class="user-image">
              <img src="../assets/usr.jpg" alt="user" />
            </div>
            <div class="user-details">
              <span>
                Sullivan Wisdom
                <span>
                  <svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M1.018 7.5H3.508C3.538 6.623 3.646 5.782 3.82 5H1.674C1.30112 5.78505 1.07861 6.63301 1.018 7.5V7.5ZM2.255 4H4.09C4.25667 3.46882 4.47087 2.95373 4.73 2.461C4.90291 2.13406 5.10259 1.82199 5.327 1.528C4.08797 2.04178 3.02196 2.89958 2.255 4V4ZM8 0C5.87827 0 3.84344 0.842855 2.34315 2.34315C0.842855 3.84344 0 5.87827 0 8C0 10.1217 0.842855 12.1566 2.34315 13.6569C3.84344 15.1571 5.87827 16 8 16C10.1217 16 12.1566 15.1571 13.6569 13.6569C15.1571 12.1566 16 10.1217 16 8C16 5.87827 15.1571 3.84344 13.6569 2.34315C12.1566 0.842855 10.1217 0 8 0V0ZM7.5 1.077C6.83 1.281 6.165 1.897 5.613 2.932C5.44 3.256 5.283 3.614 5.145 4H7.5V1.077ZM7.5 5H4.847C4.65032 5.8198 4.53707 6.6574 4.509 7.5H7.5V5ZM8.5 7.5V5H11.153C11.34 5.765 11.459 6.608 11.491 7.5H8.5ZM7.5 8.5H4.51C4.53774 9.34257 4.65065 10.1802 4.847 11H7.5V8.5ZM8.5 11V8.5H11.49C11.4623 9.34257 11.3494 10.1802 11.153 11H8.5ZM7.5 12H5.145C5.283 12.386 5.44 12.744 5.613 13.068C6.165 14.103 6.831 14.718 7.5 14.923V12ZM5.327 14.472C5.10257 14.178 4.90289 13.866 4.73 13.539C4.47087 13.0463 4.25667 12.5312 4.09 12H2.255C3.02196 13.1004 4.08797 13.9582 5.327 14.472V14.472ZM1.674 11H3.82C3.63916 10.1781 3.53471 9.34117 3.508 8.5H1.018C1.08 9.39 1.309 10.233 1.674 11ZM10.673 14.472C11.912 13.9582 12.978 13.1004 13.745 12H11.911C11.744 12.5312 11.5294 13.0463 11.27 13.539C11.0971 13.866 10.8975 14.178 10.673 14.472V14.472ZM10.855 12H8.5V14.923C9.17 14.719 9.835 14.103 10.387 13.068C10.5688 12.7239 10.7253 12.3669 10.855 12ZM12.18 11H14.326C14.691 10.233 14.92 9.39 14.982 8.5H12.492C12.4653 9.34117 12.3608 10.1781 12.18 11ZM12.492 7.5H14.982C14.9214 6.63301 14.6989 5.78506 14.326 5H12.18C12.354 5.782 12.462 6.623 12.492 7.5ZM11.91 4C11.7433 3.46884 11.5291 2.95376 11.27 2.461C11.0971 2.13404 10.8974 1.82197 10.673 1.528C11.912 2.04178 12.978 2.89958 13.745 4H11.911H11.91ZM10.855 4H8.5V1.077C9.17 1.281 9.835 1.897 10.387 2.932C10.56 3.256 10.717 3.614 10.855 4Z" fill="#2374ED" />
                  </svg>
                </span>
              </span>
              <span>Frontend Engineer</span>
              <span>
                <span>
                  <svg width="14" height="14" viewBox="0 0 14 14" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M14 6.5H10.965C10.8527 5.62025 10.4516 4.80266 9.82446 4.17554C9.19734 3.54842 8.37975 3.14726 7.5 3.035V0H6.5V3.035C5.62025 3.14726 4.80266 3.54842 4.17554 4.17554C3.54842 4.80266 3.14726 5.62025 3.035 6.5H0V7.5H3.035C3.14726 8.37975 3.54842 9.19734 4.17554 9.82446C4.80266 10.4516 5.62025 10.8527 6.5 10.965V14H7.5V10.965C8.37975 10.8527 9.19734 10.4516 9.82446 9.82446C10.4516 9.19734 10.8527 8.37975 10.965 7.5H14V6.5ZM7 10C6.40666 10 5.82664 9.82405 5.33329 9.49441C4.83994 9.16476 4.45542 8.69623 4.22836 8.14805C4.0013 7.59987 3.94189 6.99667 4.05764 6.41473C4.1734 5.83279 4.45912 5.29824 4.87868 4.87868C5.29824 4.45912 5.83279 4.1734 6.41473 4.05764C6.99667 3.94189 7.59987 4.0013 8.14805 4.22836C8.69623 4.45542 9.16476 4.83994 9.49441 5.33329C9.82405 5.82664 10 6.40666 10 7C9.99907 7.79537 9.68271 8.55789 9.1203 9.1203C8.55789 9.68271 7.79537 9.99907 7 10Z" fill="#939397" />
                  </svg>
                </span>
                Pier 3, San Francisco
              </span>
            </div>
          </div>
          <div class="profile-btns">
            <button class="button button-profile">
              <span>
                <svg width="17" height="17" viewBox="0 0 17 17" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path d="M15.7738 3.25129L12.8388 0.301294C12.6448 0.108326 12.3824 0 12.1088 0C11.8352 0 11.5727 0.108326 11.3788 0.301294L0.973774 10.6913L0.0237735 14.7913C-0.00899832 14.9412 -0.00787487 15.0965 0.0270616 15.2459C0.0619982 15.3953 0.129865 15.5349 0.225705 15.6547C0.321545 15.7745 0.442937 15.8714 0.581012 15.9383C0.719087 16.0052 0.870358 16.0404 1.02377 16.0413C1.09526 16.0485 1.16729 16.0485 1.23877 16.0413L5.38377 15.0913L15.7738 4.71129C15.9667 4.51735 16.0751 4.25488 16.0751 3.98129C16.0751 3.7077 15.9667 3.44524 15.7738 3.25129V3.25129ZM4.88377 14.1913L0.998774 15.0063L1.88377 11.1963L9.66877 3.44129L12.6688 6.44129L4.88377 14.1913ZM13.3388 5.71629L10.3388 2.71629L12.0788 0.986294L15.0288 3.98629L13.3388 5.71629Z" fill="white" />
                </svg>
              </span>
              Profile
            </button>
            <button class="button button-profile-outline">
              <span>
                <svg width="16" height="17" viewBox="0 0 16 17" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path d="M12.8054 11.1022C12.4686 11.1035 12.1356 11.1728 11.8263 11.3059C11.517 11.4391 11.2377 11.6334 11.0054 11.8772L4.91038 8.82717C5.06031 8.37255 5.06031 7.8818 4.91038 7.42717L11.0154 4.32217C11.4527 4.78299 12.0457 5.06475 12.6791 5.1127C13.3126 5.16065 13.9412 4.97136 14.4429 4.58162C14.9446 4.19188 15.2834 3.62953 15.3936 3.00388C15.5037 2.37824 15.3773 1.73398 15.0389 1.19634C14.7005 0.658699 14.1743 0.266083 13.5626 0.0948045C12.9508 -0.0764744 12.2972 -0.0141803 11.7289 0.269579C11.1605 0.553338 10.7179 1.03829 10.4872 1.63018C10.2564 2.22206 10.254 2.8786 10.4804 3.47217L4.43538 6.54717C4.1089 6.1479 3.66693 5.85937 3.17004 5.72114C2.67315 5.5829 2.14566 5.60174 1.6599 5.77506C1.17413 5.94837 0.753855 6.26769 0.456686 6.68923C0.159518 7.11078 0 7.61391 0 8.12967C0 8.64543 0.159518 9.14857 0.456686 9.57011C0.753855 9.99166 1.17413 10.311 1.6599 10.4843C2.14566 10.6576 2.67315 10.6764 3.17004 10.5382C3.66693 10.4 4.1089 10.1114 4.43538 9.71217L10.4654 12.7472C10.3635 13.0207 10.311 13.3102 10.3104 13.6022C10.3104 14.0966 10.457 14.58 10.7317 14.9911C11.0064 15.4022 11.3969 15.7227 11.8537 15.9119C12.3105 16.1011 12.8132 16.1506 13.2981 16.0541C13.7831 15.9577 14.2285 15.7196 14.5781 15.3699C14.9278 15.0203 15.1659 14.5749 15.2623 14.0899C15.3588 13.6049 15.3093 13.1023 15.1201 12.6455C14.9309 12.1886 14.6104 11.7982 14.1993 11.5235C13.7882 11.2488 13.3048 11.1022 12.8104 11.1022H12.8054ZM12.8054 1.10217C13.1021 1.10217 13.3921 1.19015 13.6387 1.35497C13.8854 1.51979 14.0777 1.75406 14.1912 2.02815C14.3047 2.30224 14.3344 2.60384 14.2766 2.89481C14.2187 3.18578 14.0758 3.45305 13.866 3.66283C13.6563 3.87261 13.389 4.01547 13.098 4.07335C12.807 4.13123 12.5054 4.10152 12.2314 3.98799C11.9573 3.87446 11.723 3.6822 11.5582 3.43553C11.3934 3.18885 11.3054 2.89884 11.3054 2.60217C11.3054 2.20435 11.4634 1.82282 11.7447 1.54151C12.026 1.26021 12.4076 1.10217 12.8054 1.10217V1.10217ZM2.54038 9.60217C2.24371 9.60217 1.9537 9.5142 1.70702 9.34938C1.46035 9.18456 1.26809 8.95029 1.15456 8.6762C1.04103 8.40211 1.01132 8.10051 1.0692 7.80954C1.12708 7.51857 1.26994 7.25129 1.47972 7.04151C1.6895 6.83173 1.95677 6.68887 2.24774 6.63099C2.53872 6.57312 2.84032 6.60282 3.1144 6.71635C3.38849 6.82988 3.62276 7.02214 3.78758 7.26882C3.95241 7.51549 4.04038 7.8055 4.04038 8.10217C4.04038 8.5 3.88234 8.88153 3.60104 9.16283C3.31974 9.44414 2.9382 9.60217 2.54038 9.60217ZM12.8054 15.1022C12.5087 15.1022 12.2187 15.0142 11.972 14.8494C11.7254 14.6846 11.5331 14.4503 11.4196 14.1762C11.306 13.9021 11.2763 13.6005 11.3342 13.3095C11.3921 13.0186 11.5349 12.7513 11.7447 12.5415C11.9545 12.3317 12.2218 12.1889 12.5127 12.131C12.8037 12.0731 13.1053 12.1028 13.3794 12.2164C13.6535 12.3299 13.8878 12.5221 14.0526 12.7688C14.2174 13.0155 14.3054 13.3055 14.3054 13.6022C14.3054 14 14.1473 14.3815 13.866 14.6628C13.5847 14.9441 13.2032 15.1022 12.8054 15.1022V15.1022Z" fill="#2a58f1" />
                </svg>
              </span>
              Share
            </button>
          </div>
          <div class="tabcard">
            <div class="tablist">
              <a href="#" class="tabitem active">Information</a>
              <a href="#" class="tabitem">Resume</a>
              <a href="#" class="tabitem">Contacts</a>
              <a href="#" class="tabitem">Teams</a>
            </div>
            <div class="tabcontent">
              <div class="tabcontent-body">
                <div class="tabcontent-child">
                  <div class="tabcontent-child-item">
                    <span>
                      <span>
                        <svg width="16" height="12" viewBox="0 0 16 12" fill="none" xmlns="http://www.w3.org/2000/svg">
                          <path d="M8.5 6C8.77614 6 9 5.77614 9 5.5C9 5.22386 8.77614 5 8.5 5C8.22386 5 8 5.22386 8 5.5C8 5.77614 8.22386 6 8.5 6Z" stroke="black" stroke-linecap="round" stroke-linejoin="round" />
                          <path d="M8 9C9.65685 9 11 7.65685 11 6C11 4.34315 9.65685 3 8 3C6.34315 3 5 4.34315 5 6C5 7.65685 6.34315 9 8 9Z" stroke="black" stroke-linecap="round" stroke-linejoin="round" />
                          <path d="M1 6C1 6 3.5 1 8 1C12.5 1 15 6 15 6C15 6 12.5 11 8 11C3.5 11 1 6 1 6Z" stroke="black" stroke-linecap="round" stroke-linejoin="round" />
                        </svg>
                      </span>
                      Project Views
                    </span>
                    <div class="item-count">12</div>
                  </div>
                  <div class="tabcontent-child-item">
                    <span>
                      <span class="heart">
                        <svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
                          <path d="M8.0001 14.4133C7.9019 14.413 7.80657 14.3802 7.72899 14.32C5.25788 12.4 3.55566 10.7467 2.36455 9.11556C0.844548 7.03112 0.497881 5.10667 1.33344 3.39556C1.92899 2.17334 3.6401 1.17334 5.6401 1.75556C6.59368 2.031 7.42565 2.62169 8.0001 3.43112C8.57456 2.62169 9.40653 2.031 10.3601 1.75556C12.3557 1.18223 14.0712 2.17334 14.6668 3.39556C15.5023 5.10667 15.1557 7.03112 13.6357 9.11556C12.4445 10.7467 10.7423 12.4 8.27122 14.32C8.19364 14.3802 8.0983 14.413 8.0001 14.4133V14.4133ZM4.50233 2.48C4.02644 2.46148 3.55449 2.57291 3.13715 2.80234C2.7198 3.03176 2.37282 3.37051 2.13344 3.78223C1.44455 5.19556 1.75566 6.76889 3.08455 8.58667C4.4968 10.4083 6.15051 12.0291 8.0001 13.4044C9.8494 12.0304 11.5031 10.4111 12.9157 8.59112C14.249 6.76889 14.5557 5.19556 13.8668 3.78667C13.4223 2.89778 12.089 2.19112 10.6045 2.60889C10.1286 2.74956 9.68731 2.98832 9.30917 3.30982C8.93104 3.63131 8.6244 4.02841 8.40899 4.47556C8.37551 4.55708 8.31855 4.6268 8.24534 4.67586C8.17214 4.72493 8.08601 4.75113 7.99788 4.75113C7.90976 4.75113 7.82362 4.72493 7.75042 4.67586C7.67722 4.6268 7.62026 4.55708 7.58677 4.47556C7.37298 4.02729 7.06687 3.62926 6.6885 3.30757C6.31013 2.98588 5.86804 2.74778 5.39122 2.60889C5.10232 2.52498 4.80316 2.48161 4.50233 2.48V2.48Z" fill="black" />
                          <path d="M14.4219 4.43126C14.2124 3.94632 13.9104 3.50687 13.5328 3.13751C13.1549 2.76705 12.7093 2.47265 12.2203 2.27032C11.7132 2.05969 11.1694 1.95187 10.6203 1.95314C9.85 1.95314 9.09844 2.16407 8.44531 2.56251C8.28906 2.65782 8.14062 2.76251 8 2.87657C7.85938 2.76251 7.71094 2.65782 7.55469 2.56251C6.90156 2.16407 6.15 1.95314 5.37969 1.95314C4.825 1.95314 4.2875 2.05939 3.77969 2.27032C3.28906 2.47345 2.84687 2.76564 2.46719 3.13751C2.08906 3.50645 1.787 3.94601 1.57812 4.43126C1.36094 4.93595 1.25 5.47189 1.25 6.02345C1.25 6.54376 1.35625 7.08595 1.56719 7.63751C1.74375 8.09845 1.99687 8.57657 2.32031 9.05939C2.83281 9.82345 3.5375 10.6203 4.4125 11.4281C5.8625 12.7672 7.29844 13.6922 7.35938 13.7297L7.72969 13.9672C7.89375 14.0719 8.10469 14.0719 8.26875 13.9672L8.63906 13.7297C8.7 13.6906 10.1344 12.7672 11.5859 11.4281C12.4609 10.6203 13.1656 9.82345 13.6781 9.05939C14.0016 8.57657 14.2562 8.09845 14.4312 7.63751C14.6422 7.08595 14.7484 6.54376 14.7484 6.02345C14.75 5.47189 14.6391 4.93595 14.4219 4.43126V4.43126Z" fill="black" />
                        </svg>
                      </span>
                      2 Projects
                    </span>
                    <div class="item-count-pill">1442</div>
                  </div>
                </div>
                <div class="tabcontent-child">
                  <div class="tabcontent-child-item">
                    <span>
                      <span>
                        <svg width="16" height="12" viewBox="0 0 16 12" fill="none" xmlns="http://www.w3.org/2000/svg">
                          <path d="M8.5 6C8.77614 6 9 5.77614 9 5.5C9 5.22386 8.77614 5 8.5 5C8.22386 5 8 5.22386 8 5.5C8 5.77614 8.22386 6 8.5 6Z" stroke="black" stroke-linecap="round" stroke-linejoin="round" />
                          <path d="M8 9C9.65685 9 11 7.65685 11 6C11 4.34315 9.65685 3 8 3C6.34315 3 5 4.34315 5 6C5 7.65685 6.34315 9 8 9Z" stroke="black" stroke-linecap="round" stroke-linejoin="round" />
                          <path d="M1 6C1 6 3.5 1 8 1C12.5 1 15 6 15 6C15 6 12.5 11 8 11C3.5 11 1 6 1 6Z" stroke="black" stroke-linecap="round" stroke-linejoin="round" />
                        </svg>
                      </span>
                      Followers
                    </span>
                    <div class="item-count">12</div>
                  </div>
                  <div class="tabcontent-child-item">
                    <span>
                      <span class="heart">
                        <svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
                          <path d="M8.0001 14.4133C7.9019 14.413 7.80657 14.3802 7.72899 14.32C5.25788 12.4 3.55566 10.7467 2.36455 9.11556C0.844548 7.03112 0.497881 5.10667 1.33344 3.39556C1.92899 2.17334 3.6401 1.17334 5.6401 1.75556C6.59368 2.031 7.42565 2.62169 8.0001 3.43112C8.57456 2.62169 9.40653 2.031 10.3601 1.75556C12.3557 1.18223 14.0712 2.17334 14.6668 3.39556C15.5023 5.10667 15.1557 7.03112 13.6357 9.11556C12.4445 10.7467 10.7423 12.4 8.27122 14.32C8.19364 14.3802 8.0983 14.413 8.0001 14.4133V14.4133ZM4.50233 2.48C4.02644 2.46148 3.55449 2.57291 3.13715 2.80234C2.7198 3.03176 2.37282 3.37051 2.13344 3.78223C1.44455 5.19556 1.75566 6.76889 3.08455 8.58667C4.4968 10.4083 6.15051 12.0291 8.0001 13.4044C9.8494 12.0304 11.5031 10.4111 12.9157 8.59112C14.249 6.76889 14.5557 5.19556 13.8668 3.78667C13.4223 2.89778 12.089 2.19112 10.6045 2.60889C10.1286 2.74956 9.68731 2.98832 9.30917 3.30982C8.93104 3.63131 8.6244 4.02841 8.40899 4.47556C8.37551 4.55708 8.31855 4.6268 8.24534 4.67586C8.17214 4.72493 8.08601 4.75113 7.99788 4.75113C7.90976 4.75113 7.82362 4.72493 7.75042 4.67586C7.67722 4.6268 7.62026 4.55708 7.58677 4.47556C7.37298 4.02729 7.06687 3.62926 6.6885 3.30757C6.31013 2.98588 5.86804 2.74778 5.39122 2.60889C5.10232 2.52498 4.80316 2.48161 4.50233 2.48V2.48Z" fill="black" />
                        </svg>
                      </span>
                      Following
                    </span>
                    <div class="item-count-pill">1442</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="md-col-1 md-pr-0 md-pl-0"></div>
      <div class="md-col-7 md-pr-0 md-pl-0">
        <div class="padded-div">
          <div class="md-col-12">
            <div class="project-pill">Projects</div>
          </div>
          <div class="columns">
            <div class="md-col-6">
              <div class="clipcard">
                <img class="clipcard-image" src="https://images.unsplash.com/photo-1509343256512-d77a5cb3791b?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=800&q=60" alt="landscape" />
                <div class="clipcard-body">Focus point</div>
              </div>
            </div>
            <div class="md-col-6">
              <div class="wavecard">
                <img class="wavecard-image" src="https://images.unsplash.com/photo-1509731987499-fd9bba3a46cc?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=800&q=60" alt="landscape" />
                <div class="wavecard-body">Ocean wave</div>
              </div>
            </div>
            <div class="md-col-6">
              <div class="clipcard">
                <img class="clipcard-image" src="https://images.unsplash.com/photo-1494253109108-2e30c049369b?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=800&q=60" alt="landscape" />
                <div class="clipcard-body">Focus point</div>
              </div>
            </div>
            <div class="md-col-6">
              <div class="wavecard">
                <img class="wavecard-image" src="https://images.unsplash.com/photo-1487700160041-babef9c3cb55?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=800&q=60" alt="landscape" />
                <div class="wavecard-body">Ocean wave</div>
              </div>
            </div>
            <div class="md-col-6">
              <div class="clipcard">
                <img class="clipcard-image" src="https://images.unsplash.com/photo-1510070009289-b5bc34383727?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=800&q=60" alt="landscape" />
                <div class="clipcard-body">Point Locus</div>
              </div>
            </div>
            <div class="md-col-6">
              <div class="wavecard">
                <img class="wavecard-image" src="https://images.unsplash.com/photo-1519643225200-94e79e383724?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=800&q=60" alt="landscape" />
                <div class="wavecard-body">Interiority</div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
</template>

<script>
export default {
  name: "Profile",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->

<style scoped>
.profilecard-desc {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding-top: 30px;
}

.user-image {
  padding-top: 10px;
}

.user-image>img {
  width: 180px;
  height: 180px;
  object-fit: cover;
  border-radius: 100%;
}

.user-details>span {
  display: block;
}

.user-details>span:first-child {
  font-size: 18px;
  font-weight: 700;
}

.user-details>span:nth-child(2) {
  padding: 5px 0;
  font-size: 16px;
  font-weight: 500;
}

.user-details>span:nth-child(3) {
  font-size: 12px;
  color: #939397;
  font-weight: 500;
}

.profile-btns {
  display: flex;
  justify-content: space-between;
  padding-top: 20px;
}

.button>span {
  position: relative;
  top: 4px;
  right: 10px;
}

.button-profile {
  padding: 12px 50px;
  background-color: rgb(42, 88, 241);
  color: #fff;
  box-shadow: 0 1px 0px 0 rgba(60, 64, 67, 0.3),
    0 1px 1px 1px rgba(60, 64, 67, 0.15);
  border-radius: 999px;
}

.button-profile-outline {
  padding: 12px 50px;
  border: 2px solid #2a58f1;
  color: rgb(42, 88, 241);
  border-radius: 999px;
}

.tabcard {
  margin-top: 50px;
}

.tablist {
  display: flex;
  justify-content: space-between;
  padding: 0 10px;
  border-radius: 30px;
}

.tablist>a {
  display: block;
  padding: 15px;
  font-size: 12px;
  text-decoration: none;
  color: rgb(105, 107, 114);
  font-weight: 500;
}

.tablist>a.active {
  color: rgb(42, 88, 241);
  background-color: #fff;
  border-top-left-radius: 30px;
}

.tabcontent {
  padding: 0 10px 20px 10px;
}

.tabcontent-body {
  background-color: #fff;
  padding: 40px;
}

.tabcontent-child {
  display: flex;
  justify-content: space-between;
  padding: 10px;
}

.item-count {
  width: 40px;
  height: 40px;
  display: flex;
  font-size: 14px;
  justify-content: center;
  align-items: center;
  margin-top: 10px;
  color: #2a58f1;
  background-color: rgba(42, 88, 241, 0.253);
  font-weight: 500;
  border-radius: 50%;
}

.item-count-pill {
  width: 60px;
  height: 40px;
  display: flex;
  justify-content: center;
  font-size: 14px;
  align-items: center;
  margin-top: 10px;
  color: rgb(42, 88, 241);
  background-color: rgba(42, 88, 241, 0.253);
  font-weight: 500;
  border-radius: 30px;
}

.project-pill {
  width: 120px;
  height: 50px;
  display: flex;
  justify-content: center;
  font-size: 14px;
  align-items: center;
  margin-top: 10px;
  color: rgb(42, 88, 241);
  background-color: rgba(42, 88, 241, 0.13);
  font-weight: 500;
  border-radius: 30px;
}

.tabcontent-child-item>span {
  font-size: 14px;
}

.tabcontent-child-item>span>.heart {
  position: relative;
  top: 3px;
}

.card {
  position: relative;
  margin: 10px 0;
  background: #ffffff;
  box-shadow: 0px 1px 4px rgba(0, 0, 0, 0.1);
  border-radius: 5px;
}

.card .card-image>img {
  width: 100%;
  height: 150px;
  object-fit: cover;
  border-top-left-radius: 5px;
  border-top-right-radius: 5px;
}

.card .card-content {
  padding: 18px;
}

.card .card-title {
  font-size: 24px;
  font-weight: 500;
}

.card .card-description {
  color: #969696;
  font-size: 14px;
  font-weight: 400;
}

.card .card-footer {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.clipcard,
.wavecard {
  margin: 30px 0;
  background: #fff;
  border-radius: 10px;
  box-shadow: 0 2px 4px 0 rgba(0, 0, 0, 0.1);
}

.clipcard-image {
  height: 200px;
  width: 100%;
  border-top-left-radius: 10px;
  border-top-right-radius: 10px;
  -webkit-clip-path: polygon(0 0,
      100% 0,
      100% 20%,
      100% 80%,
      76% 98%,
      36% 80%,
      0% 80%,
      0% 20%);
  clip-path: polygon(0 0,
      100% 0,
      100% 20%,
      100% 80%,
      76% 98%,
      36% 80%,
      0% 80%,
      0% 20%);
  object-fit: cover;
  transition: clip-path ease-in-out 0.5s;
}

.clipcard-body,
.wavecard-body {
  padding: 15px;
  color: #777;
  font-weight: 100 !important;
}

.clipcard-image:hover {
  -webkit-clip-path: polygon(0 0,
      100% 0,
      100% 20%,
      100% 80%,
      46% 80%,
      23% 90%,
      0% 80%,
      0% 20%);
  clip-path: polygon(0 0,
      100% 0,
      100% 20%,
      100% 80%,
      46% 80%,
      23% 90%,
      0% 80%,
      0% 20%);
}

.wavecard-image {
  height: 200px;
  width: 100%;
  border-top-left-radius: 10px;
  border-top-right-radius: 10px;
  -webkit-clip-path: polygon(50% 0%,
      100% 0,
      100% 43%,
      100% 75%,
      70% 84%,
      34% 64%,
      0 78%,
      0% 43%,
      0 0);
  clip-path: polygon(50% 0%,
      100% 0,
      100% 43%,
      100% 75%,
      70% 84%,
      34% 64%,
      0 78%,
      0% 43%,
      0 0);
  transition: all 0.5s ease-in-out;
}

.wavecard-image:hover {
  -webkit-clip-path: polygon(50% 0%,
      100% 0,
      100% 43%,
      100% 79%,
      66% 65%,
      36% 78%,
      0 78%,
      0% 43%,
      0 0);
  clip-path: polygon(50% 0%,
      100% 0,
      100% 43%,
      100% 79%,
      66% 65%,
      36% 78%,
      0 78%,
      0% 43%,
      0 0);
}

.padded-div {
  padding: 5px 20px;
}

@media (min-width: 768px) {
  .padded-div {
    padding: o;
  }
}
</style>
