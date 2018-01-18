<Type Name="PoolEndpointConfiguration" FullName="Microsoft.Azure.Batch.PoolEndpointConfiguration">
  <TypeSignature Language="C#" Value="public class PoolEndpointConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolEndpointConfiguration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.PoolEndpointConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolEndpointConfiguration" />
  <TypeSignature Language="F#" Value="type PoolEndpointConfiguration = class&#xA;    interface ITransportObjectProvider&lt;PoolEndpointConfiguration&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="00af7-101">Die Endpunktkonfiguration für einen Pool.</span><span class="sxs-lookup"><span data-stu-id="00af7-101">The endpoint configuration for a pool.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolEndpointConfiguration (System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.InboundNatPool&gt; inboundNatPools);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Batch.InboundNatPool&gt; inboundNatPools) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolEndpointConfiguration.#ctor(System.Collections.Generic.IReadOnlyList{Microsoft.Azure.Batch.InboundNatPool})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (inboundNatPools As IReadOnlyList(Of InboundNatPool))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.PoolEndpointConfiguration : System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.InboundNatPool&gt; -&gt; Microsoft.Azure.Batch.PoolEndpointConfiguration" Usage="new Microsoft.Azure.Batch.PoolEndpointConfiguration inboundNatPools" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="inboundNatPools" Type="System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.InboundNatPool&gt;" />
      </Parameters>
      <Docs>
        <param name="inboundNatPools"><span data-ttu-id="00af7-102">Eine Liste der eingehenden NAT-Pools, die verwendet werden kann, um bestimmte Ports auf einem einzelnen Serverknoten extern zu behandeln.</span><span class="sxs-lookup"><span data-stu-id="00af7-102">A list of inbound NAT pools that can be used to address specific ports on an individual compute node externally.</span></span></param>
        <summary>
            <span data-ttu-id="00af7-103">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.PoolEndpointConfiguration" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="00af7-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.PoolEndpointConfiguration" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InboundNatPools">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.InboundNatPool&gt; InboundNatPools { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Batch.InboundNatPool&gt; InboundNatPools" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolEndpointConfiguration.InboundNatPools" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InboundNatPools As IReadOnlyList(Of InboundNatPool)" />
      <MemberSignature Language="F#" Value="member this.InboundNatPools : System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.InboundNatPool&gt;" Usage="Microsoft.Azure.Batch.PoolEndpointConfiguration.InboundNatPools" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.InboundNatPool&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="00af7-104">Ruft eine Liste der eingehenden NAT-Pools, die verwendet werden kann, um bestimmte Ports auf einem einzelnen Serverknoten extern zu behandeln.</span><span class="sxs-lookup"><span data-stu-id="00af7-104">Gets a list of inbound NAT pools that can be used to address specific ports on an individual compute node externally.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="00af7-105">Die maximale Anzahl von eingehenden NAT-Pools pro Batch-Pool ist 5.</span><span class="sxs-lookup"><span data-stu-id="00af7-105">The maximum number of inbound NAT pools per Batch pool is 5.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>