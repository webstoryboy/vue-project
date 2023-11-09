<template>
    <footer id="footer" role="contentinfo">
        <div class="footer__inner">
            <h2 class="footer__text">
                <div>webstoryboy</div>
                <div>@webs</div>
            </h2>
            <div class="footer__info">
                <div class="left">
                    <div class="title">
                        <a href="#">sign up</a>
                    </div>
                    <p class="desc">회원가입을 하시면 댓글과 게시판 기능을 이용할 수 있습니다.</p>
                </div>
                <div class="right">
                    <h3>social</h3>
                    <ul>
                        <li>
                            <a href="https://www.youtube.com/@Webstoryboy">youtube</a>
                            <em>유튜브에 오시면 더 많은 강의를 볼 수 있습니다.</em>
                        </li>
                        <li>
                            <a href="https://github.com/webstoryboy">github</a>
                            <em>깃헙에 들어오시면 모든 소스를 볼 수 있습니다.</em>
                        </li>
                        <li>
                            <a href="https://webstoryboy.co.kr">tistory</a>
                            <em>티스토리에 들어오시면 좋은 정보 볼 수 있습니다.</em>
                        </li>
                        <li>
                            <a href="https://www.youtube.com/playlist?list=PL4UVBBIc6giL8-6jvrClimg0cFL-Muqiq">gsap</a>
                            <em>GSAP를 공부하시고 오면 도움이 됩니다.</em>
                        </li>
                        <li>
                            <a href="https://github.com/webstoryboy/port2023-vite">vite</a>
                            <em>비트 강의도 곧 오픈 예정입니다.</em>
                        </li>
                        <li>
                            <a href="https://github.com/webstoryboy/port2023-react">react</a>
                            <em>리액트 강의도 곧 오픈 예정입니다.</em>
                        </li>
                        <li>
                            <a href="https://github.com/webstoryboy/port2023-vue">vue</a>
                            <em>뷰 강의도 곧 오픈 예정입니다.</em>
                        </li>
                        <li>
                            <a href="https://github.com/webstoryboy/port2023-next">next</a>
                            <em>넥스트 강의도 곧 오픈 예정입니다.</em>
                        </li>
                    </ul>
                </div>
            </div>
            <div class="footer__right">
                &copy; 2023 webstoryboy<br />
                이 사이트는 비트를 이용하여 제작하였습니다.
            </div>
        </div>
    </footer>
</template>

<style lang="scss">
#footer {
    font-family: var(--mainKor-font);
}

.footer__inner {
    padding: 16px;
}

.footer__text {
    font-size: 12px;
    text-transform: uppercase;
    border-top: 1px solid var(--mainSub-color);
    border-bottom: 1px solid var(--mainSub-color);
    display: flex;
    justify-content: space-between;
}

.footer__info {
    display: flex;
    justify-content: space-between;
    margin: 100px 0;
}

.footer__info .left {
    width: 40%;
}

.footer__info .left .title {
    border-top: 2px solid var(--mainSub-color);
    border-bottom: 1px solid var(--mainSub-color);
    padding: 20px 0;
    text-transform: uppercase;
    font-weight: 700;
    background: url(../../img/arrow.svg) no-repeat right 20px;
    transition: all 0.3s;
    color: var(--mainSub-color);
}

.footer__info .left .title:hover {
    background-color: var(--mainSub-color);
    padding-left: 10px;
    border-color: transparent;
}

.footer__info .left .desc {
    font-size: 12px;
    padding-top: 20px;
    color: var(--mainSub-color);
}

.footer__info .right {
    width: 50%;
}

.footer__info .right h3 {
    border-top: 2px solid var(--mainSub-color);
    font-size: 10px;
    margin-bottom: 40px;
    padding-top: 10px;
    color: var(--mainSub-color);
}

.footer__info .right ul {
    border-top: 1px solid var(--mainSub-color);
}

.footer__info .right li {
    border-bottom: 1px solid var(--mainSub-color);
}

.footer__info .right li a {
    padding: 14px 0;
    font-size: 14px;
    display: inline-block;
    text-transform: uppercase;
    color: var(--mainSub-color);
}

.footer__info .right li em {
    font-size: 12px;
    padding-left: 10px;
    opacity: 0;
    transition: all 0.3s;
}

.footer__info .right li:hover em {
    opacity: 1;
}

.footer__right {
    text-align: center;
    text-transform: uppercase;
    font-size: 12px;
    margin-bottom: 20px;
    color: var(--mainSub-color);
}

@media (max-width: 800px) {
    .footer__info {
        flex-direction: column;
    }

    .footer__info .left {
        width: 100%;
    }

    .footer__info .left .desc {
        margin-bottom: 40px;
    }

    .footer__info .right {
        width: 100%;
    }
}
</style>