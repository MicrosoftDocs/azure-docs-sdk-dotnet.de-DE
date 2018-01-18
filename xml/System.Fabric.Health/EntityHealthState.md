<Type Name="EntityHealthState" FullName="System.Fabric.Health.EntityHealthState">
  <TypeSignature Language="C#" Value="public abstract class EntityHealthState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit EntityHealthState extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.EntityHealthState" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class EntityHealthState" />
  <TypeSignature Language="F#" Value="type EntityHealthState = class" />
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
      <para><span data-ttu-id="5497d-101">Stellt die Basisklasse für alle Entität Health Status Klassen dar.</span><span class="sxs-lookup"><span data-stu-id="5497d-101">Represents the base class for all entity health state classes.</span></span></para>
    </summary>
    <remarks><span data-ttu-id="5497d-102">Ein entitätsintegritätsstatus enthält Entitätsbezeichner und aggregiert entitätsintegritätsstatus.</span><span class="sxs-lookup"><span data-stu-id="5497d-102">An entity health state contains entity identifier and entity aggregated health state.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected EntityHealthState ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.EntityHealthState.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="5497d-103">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Health.EntityHealthState" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5497d-103">Initializes a new instance of the <see cref="T:System.Fabric.Health.EntityHealthState" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AggregatedHealthState">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthState AggregatedHealthState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthState AggregatedHealthState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.EntityHealthState.AggregatedHealthState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AggregatedHealthState As HealthState" />
      <MemberSignature Language="F#" Value="member this.AggregatedHealthState : System.Fabric.Health.HealthState" Usage="System.Fabric.Health.EntityHealthState.AggregatedHealthState" />
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
          <para><span data-ttu-id="5497d-104">Ruft ab, der aggregierte Integritätszustand vom Health Manager basierend auf alle gemeldeten Ereignisse und die gewünschte Richtlinie berechnet.</span><span class="sxs-lookup"><span data-stu-id="5497d-104">Gets the aggregated health state computed by Health Manager based on all reported events and the desired policy.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="5497d-105">Der aggregierte Integritätszustand vom Integritätsdienst berechnet.</span><span class="sxs-lookup"><span data-stu-id="5497d-105">The aggregated health state computed by Health Manager.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>