<Type Name="NodeImpact" FullName="System.Fabric.Repair.NodeImpact">
  <TypeSignature Language="C#" Value="public sealed class NodeImpact" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NodeImpact extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Repair.NodeImpact" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NodeImpact" />
  <TypeSignature Language="F#" Value="type NodeImpact = class" />
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
      <para>Beschreibt den erwartete Auswirkung einer Reparatur zu einem bestimmten Knoten.</para>
      <para>Diese Klasse unterstützt die Service Fabric-Plattform. Es ist nicht vorgesehen, direkt aus Ihrem Code aufgerufen werden.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeImpact ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Repair.NodeImpact.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Repair.NodeImpact" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeImpact (string nodeName, System.Fabric.Repair.NodeImpactLevel impactLevel);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string nodeName, valuetype System.Fabric.Repair.NodeImpactLevel impactLevel) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Repair.NodeImpact.#ctor(System.String,System.Fabric.Repair.NodeImpactLevel)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (nodeName As String, impactLevel As NodeImpactLevel)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Repair.NodeImpact : string * System.Fabric.Repair.NodeImpactLevel -&gt; System.Fabric.Repair.NodeImpact" Usage="new System.Fabric.Repair.NodeImpact (nodeName, impactLevel)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="impactLevel" Type="System.Fabric.Repair.NodeImpactLevel" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>Der Name des betroffenen Knoten.</para>
        </param>
        <param name="impactLevel">
          <para>Die Ebene der Auswirkungen erwartet.</para>
        </param>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Repair.NodeImpact" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImpactLevel">
      <MemberSignature Language="C#" Value="public System.Fabric.Repair.NodeImpactLevel ImpactLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Repair.NodeImpactLevel ImpactLevel" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.NodeImpact.ImpactLevel" />
      <MemberSignature Language="VB.NET" Value="Public Property ImpactLevel As NodeImpactLevel" />
      <MemberSignature Language="F#" Value="member this.ImpactLevel : System.Fabric.Repair.NodeImpactLevel with get, set" Usage="System.Fabric.Repair.NodeImpact.ImpactLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.NodeImpactLevel</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt fest, Auswirkungen erwartet.</para>
        </summary>
        <value>
          <para>Die Ebene der Auswirkungen erwartet.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.NodeImpact.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string with get, set" Usage="System.Fabric.Repair.NodeImpact.NodeName" />
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
          <para>Ruft ab oder legt den Namen des betroffenen Knotens fest.</para>
        </summary>
        <value>
          <para>Der Name des betroffenen Knoten.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Repair.NodeImpact.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="nodeImpact.ToString " />
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
          <para>Konvertiert den Wert des aktuellen Objekts in eine Zeichenfolgendarstellung.</para>
        </summary>
        <returns>
          <para>Eine Zeichenfolgendarstellung der Name und die Auswirkungen auf Knotenebene.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>