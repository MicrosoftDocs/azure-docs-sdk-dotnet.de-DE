<Type Name="StorageAccountKey" FullName="Microsoft.Azure.Management.Storage.Models.StorageAccountKey">
  <TypeSignature Language="C#" Value="public class StorageAccountKey" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StorageAccountKey extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Models.StorageAccountKey" />
  <TypeSignature Language="VB.NET" Value="Public Class StorageAccountKey" />
  <TypeSignature Language="F#" Value="type StorageAccountKey = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
    <AssemblyVersion>7.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f3afa-101">Eine Zugriffstaste für das Speicherkonto an.</span><span class="sxs-lookup"><span data-stu-id="f3afa-101">An access key for the storage account.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageAccountKey ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.StorageAccountKey.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f3afa-102">Initialisiert eine neue Instanz der StorageAccountKey-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f3afa-102">Initializes a new instance of the StorageAccountKey class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageAccountKey (string keyName = null, string value = null, Nullable&lt;Microsoft.Azure.Management.Storage.Models.KeyPermission&gt; permissions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string keyName, string value, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.KeyPermission&gt; permissions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.StorageAccountKey.#ctor(System.String,System.String,System.Nullable{Microsoft.Azure.Management.Storage.Models.KeyPermission})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional keyName As String = null, Optional value As String = null, Optional permissions As Nullable(Of KeyPermission) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Storage.Models.StorageAccountKey : string * string * Nullable&lt;Microsoft.Azure.Management.Storage.Models.KeyPermission&gt; -&gt; Microsoft.Azure.Management.Storage.Models.StorageAccountKey" Usage="new Microsoft.Azure.Management.Storage.Models.StorageAccountKey (keyName, value, permissions)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
        <Parameter Name="permissions" Type="System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.KeyPermission&gt;" />
      </Parameters>
      <Docs>
        <param name="keyName"><span data-ttu-id="f3afa-103">Der Name des Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="f3afa-103">Name of the key.</span></span></param>
        <param name="value"><span data-ttu-id="f3afa-104">Base 64-codierten Wert des Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="f3afa-104">Base 64-encoded value of the key.</span></span></param>
        <param name="permissions"><span data-ttu-id="f3afa-105">Berechtigungen für den Schlüssel – schreibgeschützt oder uneingeschränkte Berechtigungen.</span><span class="sxs-lookup"><span data-stu-id="f3afa-105">Permissions for the key -- read-only or full permissions.</span></span> <span data-ttu-id="f3afa-106">Folgende Werte sind möglich: "Lesen", "Full"</span><span class="sxs-lookup"><span data-stu-id="f3afa-106">Possible values include: 'Read', 'Full'</span></span></param>
        <summary>
            <span data-ttu-id="f3afa-107">Initialisiert eine neue Instanz der StorageAccountKey-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f3afa-107">Initializes a new instance of the StorageAccountKey class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyName">
      <MemberSignature Language="C#" Value="public string KeyName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccountKey.KeyName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property KeyName As String" />
      <MemberSignature Language="F#" Value="member this.KeyName : string" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccountKey.KeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3afa-108">Ruft den Namen des Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="f3afa-108">Gets name of the key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Permissions">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Storage.Models.KeyPermission&gt; Permissions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.KeyPermission&gt; Permissions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccountKey.Permissions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Permissions As Nullable(Of KeyPermission)" />
      <MemberSignature Language="F#" Value="member this.Permissions : Nullable&lt;Microsoft.Azure.Management.Storage.Models.KeyPermission&gt;" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccountKey.Permissions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="permissions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.KeyPermission&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3afa-109">Ruft ab, Berechtigungen für den Schlüssel – schreibgeschützt oder uneingeschränkte Berechtigungen.</span><span class="sxs-lookup"><span data-stu-id="f3afa-109">Gets permissions for the key -- read-only or full permissions.</span></span>
            <span data-ttu-id="f3afa-110">Folgende Werte sind möglich: "Lesen", "Full"</span><span class="sxs-lookup"><span data-stu-id="f3afa-110">Possible values include: 'Read', 'Full'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public string Value { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccountKey.Value" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Value As String" />
      <MemberSignature Language="F#" Value="member this.Value : string" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccountKey.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3afa-111">Ruft base 64-codierten Wert des Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="f3afa-111">Gets base 64-encoded value of the key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>