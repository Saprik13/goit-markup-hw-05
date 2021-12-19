# goit-markup-hw-05

<!-- открыть -->

@keyframes fadeInDown {
from {
opacity: 0;
transform: translate3d(0, -100%, 0);
}
to {
opacity: 1;
transform: translate3d(0, 0, 0);
}

.animate_fadeInDown {
-webkit-animation-name: fadeInDown;
animation-name: fadeInDown;
}

<!-- закрыть -->

@keyframes fadeOutDown {
from {
opacity: 1;
}

to {
opacity: 0;
transform: translate3d(0, 100%, 0);
}
.animate_fadeOutDown {
animation-name: fadeOutDown;
}
