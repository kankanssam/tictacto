:root {
    --bg-color: #f0f8ff; /* AliceBlue */
    --container-bg: #ffffff;
    --board-bg: #e6e6fa; /* Lavender */
    --cell-bg: #fafad2; /* LightGoldenRodYellow */
    --btn-bg: #add8e6; /* LightBlue */
    --btn-hover-bg: #87ceeb; /* SkyBlue */
    --btn-active-bg: #ffb6c1; /* LightPink */
    --text-color: #333;
    --x-color: #ff7f7f; /* Coral */
    --o-color: #7f7fff; /* RoyalBlue */
    --shadow-color: rgba(0, 0, 0, 0.1);
}

body {
    margin: 0;
    font-family: 'M PLUS Rounded 1c', sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background-color: var(--bg-color);
    color: var(--text-color);
}

.game-container {
    background-color: var(--container-bg);
    padding: 2rem;
    border-radius: 15px;
    box-shadow: 0 10px 20px var(--shadow-color);
    text-align: center;
    width: 90%;
    max-width: 500px;
}

h1 {
    color: var(--o-color);
}

h2, h3 {
    color: var(--text-color);
    margin-bottom: 1rem;
}

.hidden {
    display: none !important;
}

/* 게임 설정 */
#game-setup {
    display: flex;
    flex-direction: column;
    gap: 1.5rem;
}

.mode-selection, .difficulty-selection {
    display: flex;
    justify-content: center;
    gap: 10px;
}

.mode-btn, .difficulty-btn {
    flex: 1;
}

.player-inputs {
    display: flex;
    flex-direction: column;
    gap: 10px;
    margin-bottom: 1rem;
}

input[type="text"] {
    padding: 10px;
    border: 2px solid var(--board-bg);
    border-radius: 8px;
    font-size: 1rem;
}

button {
    padding: 12px 20px;
    font-size: 1rem;
    font-weight: bold;
    border: none;
    border-radius: 8px;
    background-color: var(--btn-bg);
    color: var(--text-color);
    cursor: pointer;
    transition: background-color 0.3s ease;
}

button:hover {
    background-color: var(--btn-hover-bg);
}

.active {
    background-color: var(--btn-active-bg) !important;
    color: white;
}

#start-game-btn {
    background-color: var(--x-color);
    color: white;
}

/* 게임 보드 */
#status-display {
    font-size: 1.5rem;
    margin-bottom: 1rem;
    font-weight: bold;
}

#game-board {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-template-rows: repeat(3, 1fr);
    gap: 10px;
    width: 300px;
    height: 300px;
    margin: 0 auto;
    background-color: var(--board-bg);
    padding: 10px;
    border-radius: 10px;
}

.cell {
    background-color: var(--cell-bg);
    border-radius: 8px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 4rem;
    font-weight: bold;
    cursor: pointer;
    user-select: none;
}

.cell.x { color: var(--x-color); }
.cell.o { color: var(--o-color); }

#reset-btn {
    margin-top: 1.5rem;
}

/* 게임 종료 모달 */
#game-over-modal {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.5);
    display: flex;
    justify-content: center;
    align-items: center;
}

.modal-content {
    background-color: white;
    padding: 2rem 3rem;
    border-radius: 15px;
    text-align: center;
}

#game-over-message {
    font-size: 1.8rem;
    margin-bottom: 1.5rem;
}

/* 반응형 디자인 */
@media (max-width: 480px) {
    .game-container {
        padding: 1rem;
    }
    #game-board {
        width: 80vw;
        height: 80vw;
    }
    .cell {
        font-size: 10vw;
    }
    #status-display {
        font-size: 1.2rem;
    }
}