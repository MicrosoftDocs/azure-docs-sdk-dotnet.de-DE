<Type Name="EncryptionIdentity" FullName="Microsoft.Azure.Management.DataLake.Store.Models.EncryptionIdentity">
  <TypeSignature Language="C#" Value="public class EncryptionIdentity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi EncryptionIdentity extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.Models.EncryptionIdentity" />
  <TypeSignature Language="VB.NET" Value="Public Class EncryptionIdentity" />
  <TypeSignature Language="F#" Value="type EncryptionIdentity = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="31dac-101">Die Identitätseigenschaften der Verschlüsselung.</span><span class="sxs-lookup"><span data-stu-id="31dac-101">The encryption identity properties.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EncryptionIdentity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.EncryptionIdentity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="31dac-102">Initialisiert eine neue Instanz der EncryptionIdentity-Klasse.</span><span class="sxs-lookup"><span data-stu-id="31dac-102">Initializes a new instance of the EncryptionIdentity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EncryptionIdentity (Nullable&lt;Guid&gt; principalId = null, Nullable&lt;Guid&gt; tenantId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.Guid&gt; principalId, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; tenantId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.EncryptionIdentity.#ctor(System.Nullable{System.Guid},System.Nullable{System.Guid})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional principalId As Nullable(Of Guid) = null, Optional tenantId As Nullable(Of Guid) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Store.Models.EncryptionIdentity : Nullable&lt;Guid&gt; * Nullable&lt;Guid&gt; -&gt; Microsoft.Azure.Management.DataLake.Store.Models.EncryptionIdentity" Usage="new Microsoft.Azure.Management.DataLake.Store.Models.EncryptionIdentity (principalId, tenantId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="principalId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="tenantId" Type="System.Nullable&lt;System.Guid&gt;" />
      </Parameters>
      <Docs>
        <param name="principalId"><span data-ttu-id="31dac-103">Der prinzipalbezeichner die Verschlüsselung zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="31dac-103">The principal identifier associated with the encryption.</span></span></param>
        <param name="tenantId"><span data-ttu-id="31dac-104">Der mandantenbezeichner, der die Verschlüsselung zugeordnet wird.</span><span class="sxs-lookup"><span data-stu-id="31dac-104">The tenant identifier associated with the encryption.</span></span></param>
        <summary>
            <span data-ttu-id="31dac-105">Initialisiert eine neue Instanz der EncryptionIdentity-Klasse.</span><span class="sxs-lookup"><span data-stu-id="31dac-105">Initializes a new instance of the EncryptionIdentity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrincipalId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; PrincipalId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; PrincipalId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.EncryptionIdentity.PrincipalId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PrincipalId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.PrincipalId : Nullable&lt;Guid&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.Models.EncryptionIdentity.PrincipalId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="principalId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="31dac-106">Ruft den prinzipalbezeichner die Verschlüsselung zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="31dac-106">Gets the principal identifier associated with the encryption.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TenantId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; TenantId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; TenantId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.EncryptionIdentity.TenantId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TenantId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.TenantId : Nullable&lt;Guid&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.Models.EncryptionIdentity.TenantId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tenantId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="31dac-107">Ruft die Mandanten-ID, die die Verschlüsselung zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="31dac-107">Gets the tenant identifier associated with the encryption.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public static string Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.EncryptionIdentity.Type" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string" Usage="Microsoft.Azure.Management.DataLake.Store.Models.EncryptionIdentity.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="31dac-108">Der Typ der Verschlüsselung verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="31dac-108">The type of encryption being used.</span></span> <span data-ttu-id="31dac-109">Derzeit ist der einzige unterstützte Typ "SystemAssigned".</span><span class="sxs-lookup"><span data-stu-id="31dac-109">Currently the only supported type is 'SystemAssigned'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>