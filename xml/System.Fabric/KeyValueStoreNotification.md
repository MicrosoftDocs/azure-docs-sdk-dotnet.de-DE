<Type Name="KeyValueStoreNotification" FullName="System.Fabric.KeyValueStoreNotification">
  <TypeSignature Language="C#" Value="public sealed class KeyValueStoreNotification" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit KeyValueStoreNotification extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.KeyValueStoreNotification" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class KeyValueStoreNotification" />
  <TypeSignature Language="F#" Value="type KeyValueStoreNotification = class" />
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
      <para><span data-ttu-id="3cf21-101">Enthält alle Informationen für eine replizierte Vorgang von einem sekundären Replikat empfangen.</span><span class="sxs-lookup"><span data-stu-id="3cf21-101">Contains all the information for a replicated operation received by a secondary replica.</span></span></para>
    </summary>
    <remarks>
      <para><span data-ttu-id="3cf21-102">Weitere Informationen finden Sie unter <see cref="M:System.Fabric.KeyValueStoreReplica.OnReplicationOperation(System.Collections.Generic.IEnumerator{System.Fabric.KeyValueStoreNotification})" />.</span><span class="sxs-lookup"><span data-stu-id="3cf21-102">See <see cref="M:System.Fabric.KeyValueStoreReplica.OnReplicationOperation(System.Collections.Generic.IEnumerator{System.Fabric.KeyValueStoreNotification})" />.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="IsDelete">
      <MemberSignature Language="C#" Value="public bool IsDelete { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDelete" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.KeyValueStoreNotification.IsDelete" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsDelete As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDelete : bool" Usage="System.Fabric.KeyValueStoreNotification.IsDelete" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="3cf21-103">Gibt an, dass dies eine replizierte Löschvorgang ist.</span><span class="sxs-lookup"><span data-stu-id="3cf21-103">Indicates that this is a replicated delete operation.</span></span></para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="3cf21-104"><languageKeyword>"true"</languageKeyword> ist dies eine replizierte Löschvorgang; andernfalls <languageKeyword>"false"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="3cf21-104"><languageKeyword>true</languageKeyword> if this is a replicated delete operation; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Fabric.KeyValueStoreItemMetadata Metadata { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.KeyValueStoreItemMetadata Metadata" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.KeyValueStoreNotification.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Metadata As KeyValueStoreItemMetadata" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Fabric.KeyValueStoreItemMetadata" Usage="System.Fabric.KeyValueStoreNotification.Metadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.KeyValueStoreItemMetadata</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="3cf21-105">Ruft ab oder legt die Metadaten zum Beschreiben dieser replizierten Vorgang.</span><span class="sxs-lookup"><span data-stu-id="3cf21-105">Gets or sets the metadata describing this replicated operation.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="3cf21-106">Die Metadaten zum Beschreiben dieser repliziert Vorgang.</span><span class="sxs-lookup"><span data-stu-id="3cf21-106">The metadata describing this replicated operation.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public byte[] Value { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] Value" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.KeyValueStoreNotification.Value" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Value As Byte()" />
      <MemberSignature Language="F#" Value="member this.Value : byte[]" Usage="System.Fabric.KeyValueStoreNotification.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="3cf21-107">Ruft ab oder legt ihn fest die Daten (sofern vorhanden) für diesen Vorgang replizierten.</span><span class="sxs-lookup"><span data-stu-id="3cf21-107">Gets or sets the data (if any) for this replicated operation.</span></span> <span data-ttu-id="3cf21-108">NULL, wenn dies ein Löschvorgang ist.</span><span class="sxs-lookup"><span data-stu-id="3cf21-108">Null if this is a delete operation.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="3cf21-109">Die Daten (sofern vorhanden) für dieses repliziert Vorgang.</span><span class="sxs-lookup"><span data-stu-id="3cf21-109">The data (if any) for this replicated operation.</span></span> <span data-ttu-id="3cf21-110">NULL, wenn dies ein Löschvorgang ist.</span><span class="sxs-lookup"><span data-stu-id="3cf21-110">Null if this is a delete operation.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>