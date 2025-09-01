<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Programa Sorte Cresce+ - Sistema de Fidelização</title>
    <style>
        :root {
            --primary: #2ECC71;
            --secondary: #F39C12;
            --accent: #3498DB;
            --dark: #2C3E50;
            --light: #f8f9fa;
        }
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f5f5f5;
        }
        .container {
            background: white;
            border-radius: 15px;
            padding: 30px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            margin-bottom: 30px;
        }
        h1, h2, h3 {
            color: var(--dark);
        }
        h1 {
            text-align: center;
            color: var(--primary);
            margin-bottom: 10px;
        }
        .subtitle {
            text-align: center;
            color: var(--secondary);
            font-size: 1.2em;
            margin-bottom: 30px;
        }
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin: 30px 0;
        }
        .card {
            background: var(--light);
            padding: 20px;
            border-radius: 10px;
            border-left: 5px solid var(--accent);
        }
        .card h3 {
            margin-top: 0;
            color: var(--accent);
        }
        .highlight {
            background-color: #FFF8E1;
            padding: 15px;
            border-radius: 8px;
            border-left: 5px solid var(--secondary);
            margin: 20px 0;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
        }
        th, td {
            padding: 12px 15px;
            text-align: left;
            border-bottom: 1px solid #ddd;
        }
        th {
            background-color: var(--primary);
            color: white;
        }
        tr:hover {
            background-color: #f5f5f5;
        }
        .lottery-model {
            background: linear-gradient(135deg, #E8F5E9 0%, #E3F2FD 100%);
            padding: 25px;
            border-radius: 10px;
            margin: 25px 0;
        }
        .benefits {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            margin: 25px 0;
        }
        .benefit-item {
            flex: 1;
            min-width: 250px;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
        }
        .benefit-icon {
            font-size: 2.5em;
            color: var(--secondary);
            margin-bottom: 15px;
            text-align: center;
        }
        .conclusion {
            background: linear-gradient(135deg, var(--primary) 0%, var(--accent) 100%);
            color: white;
            padding: 30px;
            border-radius: 10px;
            text-align: center;
            margin-top: 40px;
        }
        .cta-button {
            display: inline-block;
            background: var(--secondary);
            color: white;
            padding: 15px 30px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: bold;
            margin-top: 20px;
            transition: all 0.3s;
        }
        .cta-button:hover {
            background: #E67E22;
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>PROGRAMA SORTE CRESCE+</h1>
        <p class="subtitle">Sistema visionário de fidelização através de sorteios mensais</p>
        
        <h2>Por que substituir os grupos de 5 por sorteios?</h2>
        
        <div class="grid">
            <div class="card">
                <h3>🎯 Maior Atração de Clientes</h3>
                <p>O sistema de sorteios é mais atraente e menos intimidante do que a responsabilidade compartilhada dos grupos.</p>
            </div>
            <div class="card">
                <h3>📈 Redução de Complexidade</h3>
                <p>Elimina a necessidade de gerenciar dinâmicas de grupo e conflitos entre participantes.</p>
            </div>
            <div class="card">
                <h3>💰 Custo-Benefício Superior</h3>
                <p>Os prêmios dos sorteios custam menos do que o trabalho operacional para gerenciar grupos de 5.</p>
            </div>
        </div>
        
        <div class="highlight">
            <h3>🚀 Vantagem Estratégica:</h3>
            <p>O programa de sorteios cria um ciclo virtuoso: mais clientes → mais sorteios → mais engajamento → mais clientes.</p>
        </div>
    </div>
    
    <div class="container">
        <h2>Como Funcionaria o Programa Sorte Cresce+</h2>
        
        <div class="lottery-model">
            <h3>Modelo de Sorteios Mensais</h3>
            
            <table>
                <thead>
                    <tr>
                        <th>Nível de Cliente</th>
                        <th>Como Participar</th>
                        <th>Prêmios Mensais</th>
                        <th>Prêmio Anual</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td><strong>Iniciante</strong> (1-3 empréstimos)</td>
                        <td>1 cupom a cada R$ 100 pagos em dia</td>
                        <td>5 kits ferramentas (R$ 200 cada)</td>
                        <td>1 moto popular</td>
                    </tr>
                    <tr>
                        <td><strong>Intermediário</strong> (4-6 empréstimos)</td>
                        <td>2 cupons a cada R$ 100 pagos em dia</td>
                        <td>3 tablets + crédito (R$ 800 cada)</td>
                        <td>1 carro popular</td>
                    </tr>
                    <tr>
                        <td><strong>Avançado</strong> (7+ empréstimos)</td>
                        <td>3 cupons a cada R$ 100 pagos em dia + bônus</td>
                        <td>2 microcréditos sem juros (R$ 2.000)</td>
                        <td>1 reforma de estabelecimento (R$ 15.000)</td>
                    </tr>
                </tbody>
            </table>
            
            <p><strong>Regras transparentes:</strong> Sorteios mensais transmitidos ao vivo pelas redes sociais com auditoria externa.</p>
        </div>
        
        <h3>Mecânica de Pontuação e Vantagens:</h3>
        <ul>
            <li>Clientes ganham <strong>cupons</strong> para os sorteios conforme pagam em dia</li>
            <li>Pagamentos antecipados geram <strong>cupons bônus</strong></li>
            <li>Indicações de novos clientes validados geram <strong>cupons extras</strong></li>
            <li>Participação em oficinas de educação financeira concede <strong>vantagens especiais</strong></li>
        </ul>
    </div>
    
    <div class="container">
        <h2>Vantagens do Sistema de Sorteios</h2>
        
        <div class="benefits">
            <div class="benefit-item">
                <div class="benefit-icon">📊</div>
                <h3>Melhora a Inadimplência</h3>
                <p>Clientes têm incentivo extra para pagar em dia e não perder os cupons dos sorteios.</p>
            </div>
            <div class="benefit-item">
                <div class="benefit-icon">👥</div>
                <h3>Gera Engajamento Orgânico</h3>
                <p>Os sorteios mensais criam buzz marketing e incentivam indicações.</p>
            </div>
            <div class="benefit-item">
                <div class="benefit-icon">💡</div>
                <h3>Substitui a Pressão dos Grupos</h3>
                <p>Mantém o aspecto comunitário sem a responsabilidade solidária forçada.</p>
            </div>
            <div class="benefit-item">
                <div class="benefit-icon">📱</div>
                <h3>Gera Conteúdo Digital</h3>
                <p>Os sorteios ao vivo geram conteúdo para redes sociais e marketing digital.</p>
            </div>
        </div>
        
        <div class="highlight">
            <h3>📈 Projeção de Resultados:</h3>
            <p>Com investimento de 5% do faturamento em prêmios, é possível reduzir a inadimplência em 30-40% e aumentar a retenção de clientes em 60%.</p>
        </div>
    </div>
    
    <div class="container">
        <h2>Implementação em 3 Fases</h2>
        
        <table>
            <thead>
                <tr>
                    <th>Fase</th>
                    <th>Duração</th>
                    <th>Ações</th>
                    <th>Investimento</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td><strong>Piloto</strong></td>
                    <td>3 meses</td>
                    <td>Sorteios simples com prêmios simbólicos, teste de engajamento</td>
                    <td>R$ 5.000/mês</td>
                </tr>
                <tr>
                    <td><strong>Expansão</strong></td>
                    <td>6 meses</td>
                    <td>Integração com app, sistema de cupons, prêmios maiores</td>
                    <td>R$ 15.000/mês</td>
                </tr>
                <tr>
                    <td><strong>Consolidação</strong></td>
                    <td>Contínuo</td>
                    <td>Sorteios transmitidos ao vivo, prêmios anuais, parcerias</td>
                    <td>R$ 25.000/mês (5% do faturamento)</td>
                </tr>
            </tbody>
        </table>
    </div>
    
    <div class="conclusion">
        <h2>Conclusão Estratégica</h2>
        <p>O programa <strong>Sorte Cresce+</strong> representa uma evolução do modelo de grupos solidários, mantendo os benefícios de comunidade e responsabilidade compartilhada, mas sem os aspectos negativos da dependência grupal.</p>
        <p>Esta abordagem é mais adequada à cultura brasileira contemporânea e tem potencial para gerar maior engajamento, redução de inadimplência e atração de novos clientes.</p>
        <p><strong>Próximo passo recomendado:</strong> Implementar projeto piloto com 100 clientes para validar a aceitação e ajustar a mecânica de sorteios.</p>
        <a href="#" class="cta-button">Quero implementar o Sorte Cresce+</a>
    </div>
</body>
</html>
            <p>"Plantando crédito, colhendo oportunidades."</p>
            <p>&copy; 2023 CRESCE+. Todos os direitos reservados.</p>
        </div>
    </footer>
</body>
</html>
