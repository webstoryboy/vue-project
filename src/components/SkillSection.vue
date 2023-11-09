<template>
    <section id="skill">
        <div class="skill__inner">
            <h2 class="skill__title">
                challenge <em>나의 도전</em>
            </h2>
            <div class="skill__desc">
                <div>
                    <span>1.</span>
                    <h3>꿈을 설계하고 디자인하다.</h3>
                    <p>
                        나는 공간을 만드는 것을 좋아한다.
                        어려을 때부터 나만의 공간을 만드는 것을 좋아했고 나만의 다락방을 좋아했다.
                        단 한 사람이라도 내가 만든 공간 속에서 영감을 받거나 마음이 움직였으면 좋겠다.
                        나만의 공간을 마음것 만들 수 있다는 건 코딩에 엄청난 매력인거 같다.
                        그 한구석에 나만의 꿈을 설계하고, 개발을 하며 앞으로도 살고 싶다.
                    </p>
                </div>
                <div>
                    <span>2.</span>
                    <h3>열심히 할수록 기회는 따른다.</h3>
                    <p>
                        운이 좋은 사람은 없다. 단지 운을 만들 뿐이다.
                        운을 만들기 위해서는 내가 좋아하는 일이나 내가 하고 싶은 일에 몰두하면 된다.
                        몰두 하다보면 길이 보이고 방향이 보이게 된다.
                        운이란 고된 노동과 노력을 통해 스스로 만들어 내는 것이다.
                    </p>
                </div>
                <div>
                    <span>3.</span>
                    <h3>나에게 정직하다.</h3>
                    <p>
                        정직은 다른 사람보다 나에게 큰 의미를 부여해야 한다.
                        자신이 정직하지 않으면 진정으로 원하는 일을 열정적으로 밀고 나갈 수 없다.
                        마음에서 우러나오는 일을 해야 정직해지며 삶을 더 즐길 줄 알게 된다.
                    </p>
                </div>
            </div>
        </div>
    </section>
</template>

<style lang="scss">
.skill__inner {
    padding: 16px;
    display: flex;
    justify-content: space-between;
}

.skill__title {
    position: sticky;
    top: 65px;
    left: 0;
    width: 48%;
    height: 4.9vw;
    font-size: 4vw;
    font-weight: 900;
    line-height: 1.6;
    text-transform: uppercase;
    font-family: var(--mainPop-font);
    border-bottom: 0.4vw solid var(--white200);
    color: var(--white200);
}

.skill__title em {
    font-family: var(--mainKor-font);
    font-size: 1.25rem;
    font-weight: 400;
    display: inline-block;
    vertical-align: 4px;
}

.skill__desc {
    width: 50%;
}

.skill__desc span {
    font-size: 5vw;
    line-height: 1.5;
    font-weight: 900;
    font-family: var(--mainNum-font);
    color: var(--white200);
}

.skill__desc h3 {
    font-size: 1.5rem;
    text-decoration: underline;
    text-underline-position: under;
    margin-bottom: 1vw;
    color: var(--white200);
}

.skill__desc p {
    margin-bottom: 30vh;
    font-size: 1.1rem;
    font-family: var(--mainKor-font);
    color: var(--white200);
}

@media (max-width: 800px) {
    .skill__inner {
        flex-direction: column;
    }

    .skill__title {
        width: 100%;
        margin-bottom: 10vw;
        height: auto;
        background-color: var(--mainBg-color);
        font-size: 40px;
        line-height: 1.4;
        top: 68px;
    }

    .skill__desc {
        width: 100%;
    }

    .skill__desc span {
        font-size: 20vw;
    }

    .skill__desc h3 {
        font-size: 24px;
        margin-bottom: 2vw;
    }

    .skill__desc p {
        font-size: 16px;
    }
}</style>