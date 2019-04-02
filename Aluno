package br.org.lasalle.semana3;

import java.util.ArrayList;

public class Aluno {
	
	private String matricula;
	private String nome;
	private String curso;
	
	public ArrayList<Disciplina> disciplinas;
	
	//criar um construtor para Aluno
	public Aluno()
	{
		this.curso = "Direito";
		this.disciplinas = new ArrayList<Disciplina>();
	}
	
	public Aluno(String curso)
	{
		this.curso = curso;
	}
	
	
	public void setMatricula(String mat)
	{
		this.matricula = mat;
	}
	
	public String getMatricula()
	{
		return this.matricula;
	}
	
	
	public void mostrarLog()
	{
		System.out.println("Matricula =" + this.matricula);
		System.out.println("Nome =" + this.nome);
		System.out.println("Curso =" + this.curso);
		
		System.out.println("matriculado nas disciplinas:");
		for (int i = 0; i < this.disciplinas.size(); i++) {
			System.out.println(" #"+i+": " + disciplinas.get(i).getDescricao());
		}
	}

	public String getNome() {
		return this.nome;
	}

	public void setNome(String nome) {
		this.nome = nome;
	}

	public String getCurso() {
		return this.curso;
	}

	public void setCurso(String curso) {
		if (curso.equalsIgnoreCase("si"))
			this.curso = "Sistemas de Informa��o";
		else
			this.curso = curso;
	}

}
