import Link from "next/link";

export default function Home() {
  return (
    <div style={{ padding: 24, fontFamily: "Arial, sans-serif" }}>
      <h1>ScriptBru - Repositório de Estudos</h1>
      <nav>
        <ul>
          <li><Link href="/summaries">Resumos por Bimestre</Link></li>
          <li><Link href="/quiz">Questões Simuladas</Link></li>
          <li><Link href="/flashcards">Flashcards</Link></li>
          <li><Link href="/tools">Ferramentas de Estudo</Link></li>
        </ul>
      </nav>
    </div>
  );
}
