<Type Name="NodeRepairImpactDescription" FullName="System.Fabric.Repair.NodeRepairImpactDescription">
  <TypeSignature Language="C#" Value="public sealed class NodeRepairImpactDescription : System.Fabric.Repair.RepairImpactDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NodeRepairImpactDescription extends System.Fabric.Repair.RepairImpactDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Repair.NodeRepairImpactDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NodeRepairImpactDescription&#xA;Inherits RepairImpactDescription" />
  <TypeSignature Language="F#" Value="type NodeRepairImpactDescription = class&#xA;    inherit RepairImpactDescription" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Repair.RepairImpactDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Stellt die erwartete Auswirkung der Reparatur eines eine Gruppe von Knoten dar.</para>
      <para>Diese Klasse unterstützt die Service Fabric-Plattform. Es ist nicht vorgesehen, direkt aus Ihrem Code aufgerufen werden.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeRepairImpactDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Repair.NodeRepairImpactDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.Repair.NodeRepairImpactDescription" /> Klasse mit einer leeren auswirkungsliste.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImpactedNodes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Repair.NodeImpact&gt; ImpactedNodes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Repair.NodeImpact&gt; ImpactedNodes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.NodeRepairImpactDescription.ImpactedNodes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ImpactedNodes As IList(Of NodeImpact)" />
      <MemberSignature Language="F#" Value="member this.ImpactedNodes : System.Collections.Generic.IList&lt;System.Fabric.Repair.NodeImpact&gt;" Usage="System.Fabric.Repair.NodeRepairImpactDescription.ImpactedNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Repair.NodeImpact&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Liste der betroffenen Knoten ab.</para>
        </summary>
        <value>
          <para>Eine Liste der <see cref="T:System.Fabric.Repair.NodeImpact" /> Objekten, die die Auswirkungen der Reparatur beschreiben.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Repair.NodeRepairImpactDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="nodeRepairImpactDescription.ToString " />
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
          <para>Eine Zeichenfolgendarstellung des Werts der <see cref="P:System.Fabric.Repair.NodeRepairImpactDescription.ImpactedNodes" />.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>