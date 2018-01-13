<Type Name="HealthEvaluation" FullName="System.Fabric.Health.HealthEvaluation">
  <TypeSignature Language="C#" Value="public abstract class HealthEvaluation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit HealthEvaluation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class HealthEvaluation" />
  <TypeSignature Language="F#" Value="type HealthEvaluation = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Stellt eine integritätsauswertung, die die Daten und den Algorithmus, die vom Health Store verwendet werden, um den Zustand einer Entität auszuwerten beschreibt.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected HealthEvaluation (System.Fabric.Health.HealthEvaluationKind kind);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.Health.HealthEvaluationKind kind) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.HealthEvaluation.#ctor(System.Fabric.Health.HealthEvaluationKind)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (kind As HealthEvaluationKind)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Health.HealthEvaluation : System.Fabric.Health.HealthEvaluationKind -&gt; System.Fabric.Health.HealthEvaluation" Usage="new System.Fabric.Health.HealthEvaluation kind" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="kind" Type="System.Fabric.Health.HealthEvaluationKind" />
      </Parameters>
      <Docs>
        <param name="kind">
          <para>Die <see cref="T:System.Fabric.Health.HealthEvaluationKind" /> der Auswertung.</para>
        </param>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Health.HealthEvaluation" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AggregatedHealthState">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthState AggregatedHealthState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthState AggregatedHealthState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthEvaluation.AggregatedHealthState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AggregatedHealthState As HealthState" />
      <MemberSignature Language="F#" Value="member this.AggregatedHealthState : System.Fabric.Health.HealthState" Usage="System.Fabric.Health.HealthEvaluation.AggregatedHealthState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Der aggregierte Integritätszustand der ausgewerteten Entität.</para>
        </summary>
        <value>
          <para>Ein <see cref="T:System.Fabric.Health.HealthState" /> , der aggregierte Integritätszustand darstellt.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthEvaluation.Description" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string" Usage="System.Fabric.Health.HealthEvaluation.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Beschreibung der integritätsauswertung, die eine Zusammenfassung der Bewertungsprozess darstellt.</para>
        </summary>
        <value>
          <para>Ein <see cref="T:System.String" /> , die die Beschreibung der integritätsauswertung darstellt.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthEvaluationKind Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthEvaluationKind Kind" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthEvaluation.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As HealthEvaluationKind" />
      <MemberSignature Language="F#" Value="member this.Kind : System.Fabric.Health.HealthEvaluationKind" Usage="System.Fabric.Health.HealthEvaluation.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthEvaluationKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Art der integritätsauswertung.</para>
        </summary>
        <value>
          <para>Ein <see cref="T:System.Fabric.Health.HealthEvaluationKind" /> der integritätsauswertung.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.HealthEvaluation.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="healthEvaluation.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Gibt eine Zeichenfolgendarstellung der Bewertung der Netzwerkintegrität zurück.
            </summary>
        <returns>Eine Zeichenfolgendarstellung der integritätsauswertung.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>