# computer_visioin
1. Atlas
2. Neural Recon
3. Scannet dataset

install git
https://www.lainyzine.com/ko/article/how-to-set-git-repository-username-and-email/

git clone "the https address..."
git submodule --init --recursive >>> enable to clone submodules, too.
https://nochoco-lee.tistory.com/87

anaconda install 
https://ieworld.tistory.com/12

vim, build-essential install

linux_cuda install(nvcc)
https://tutorialforlinux.com/2021/04/08/step-by-step-cuda-ubuntu-21-04-installation-guide/
https://renai21c.gitbooks.io/linux-nvidia-cuda/content/chapter2.html
2.4까지 함.

flameshot install(screenshot program)
https://ieworld.tistory.com/19?category=876039c

cuda 설치방법
혹시 기존에 nvidia driver가 깔려있다면 삭제후 cuda 버전에 맞는 것 설치

# nvidia driver 삭제
sudo apt-get --purge remove *nvidia*
# 의존성 패키지로 남은 것들 삭제
sudo apt-get autoremove 
# cuda 11.2 
https://sanglee325.github.io/environment/install-CUDA-11-2/#11-%EC%97%90%EB%9F%AC%EA%B0%80-%EB%B0%9C%EC%83%9D%ED%95%9C-%EA%B2%BD%EC%9A%B0-building-kernel-modules
