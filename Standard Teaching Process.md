
<div class="mermaid">
graph TD;
A(Selection of Text);
B(3 Weeks Course Program);
C(Part of Traditional Pariyatti Content);
D(Standard Class Template);
E(Translation to be Proofread);
F(Problem to be solved);
G(Featured Q&A);
H(Translation already Proofread);
I(Translation Library);
J(Q&A Library);
K(Text of Speech);
L(Standard Video Recording);
M(Actual Speech);
N(Feedback);
subgraph Course Design
A--Teacher Selection-->C;
B-->C;
C--Extract Relevance from Pali Texts by Teacher/Monitor-->D;
end;
subgraph Translation&Data mining
D--Class Preview led by Monitor-->E;
E--Proofread by Teacher in Live zoom room-->H;
H--Filing-->I;
end
subgraph FAQ Building
D--Key questions collected by Monitor-->F;
F--Teacher's Answer-->G;
G--Filing-->J;
J--Search assistant-->F;
end
subgraph Stage Assessment
I--Featured course rehearsal-->K;
K--Teacher's speech-->L;
K--Student's speech-->M;
M--Audience_Parents-->N;
end
</div>
