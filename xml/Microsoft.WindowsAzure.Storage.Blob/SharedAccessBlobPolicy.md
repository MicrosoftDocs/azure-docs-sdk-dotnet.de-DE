<Type Name="SharedAccessBlobPolicy" FullName="Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy">
  <TypeSignature Language="C#" Value="public sealed class SharedAccessBlobPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SharedAccessBlobPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SharedAccessBlobPolicy" />
  <TypeSignature Language="F#" Value="type SharedAccessBlobPolicy = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b2116-101">Stellt eine SAS-Richtlinie, die die Startzeit, Ablaufzeit und Berechtigungen für eine SAS angibt.</span><span class="sxs-lookup"><span data-stu-id="b2116-101">Represents a shared access policy, which specifies the start time, expiry time, and permissions for a shared access signature.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedAccessBlobPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b2116-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="b2116-102">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Permissions">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPermissions Permissions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPermissions Permissions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy.Permissions" />
      <MemberSignature Language="VB.NET" Value="Public Property Permissions As SharedAccessBlobPermissions" />
      <MemberSignature Language="F#" Value="member this.Permissions : Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPermissions with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy.Permissions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPermissions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b2116-103">Ruft ab oder legt die Berechtigungen für eine shared Access Signature, die mit dieser SAS-Richtlinie verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="b2116-103">Gets or sets the permissions for a shared access signature associated with this shared access policy.</span></span>
            </summary>
        <value><span data-ttu-id="b2116-104">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPermissions" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="b2116-104">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPermissions" /> object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PermissionsFromString">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPermissions PermissionsFromString (string input);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig valuetype Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPermissions PermissionsFromString(string input) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy.PermissionsFromString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function PermissionsFromString (input As String) As SharedAccessBlobPermissions" />
      <MemberSignature Language="F#" Value="static member PermissionsFromString : string -&gt; Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPermissions" Usage="Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy.PermissionsFromString input" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPermissions</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="input" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="input"><span data-ttu-id="b2116-105">Die SAS-Berechtigungen im Zeichenfolgenformat.</span><span class="sxs-lookup"><span data-stu-id="b2116-105">The shared access permissions, in string format.</span></span></param>
        <summary>
            <span data-ttu-id="b2116-106">Erstellt eine <see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPermissions" /> Objekt aus einer Berechtigungszeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="b2116-106">Constructs a <see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPermissions" /> object from a permissions string.</span></span>
            </summary>
        <returns><span data-ttu-id="b2116-107">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPermissions" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="b2116-107">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPermissions" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PermissionsToString">
      <MemberSignature Language="C#" Value="public static string PermissionsToString (Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPermissions permissions);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string PermissionsToString(valuetype Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPermissions permissions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy.PermissionsToString(Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPermissions)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function PermissionsToString (permissions As SharedAccessBlobPermissions) As String" />
      <MemberSignature Language="F#" Value="static member PermissionsToString : Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPermissions -&gt; string" Usage="Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy.PermissionsToString permissions" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissions" Type="Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPermissions" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="b2116-108">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPermissions" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="b2116-108">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPermissions" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="b2116-109">Konvertiert die Berechtigungen für die SAS-Richtlinie in eine Zeichenfolge angegeben.</span><span class="sxs-lookup"><span data-stu-id="b2116-109">Converts the permissions specified for the shared access policy to a string.</span></span>
            </summary>
        <returns><span data-ttu-id="b2116-110">Die SAS-Berechtigungen im Zeichenfolgenformat.</span><span class="sxs-lookup"><span data-stu-id="b2116-110">The shared access permissions, in string format.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessExpiryTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; SharedAccessExpiryTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; SharedAccessExpiryTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy.SharedAccessExpiryTime" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessExpiryTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.SharedAccessExpiryTime : Nullable&lt;DateTimeOffset&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy.SharedAccessExpiryTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b2116-111">Ruft ab oder legt die Ablaufzeit für eine shared Access Signature, die mit dieser SAS-Richtlinie verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="b2116-111">Gets or sets the expiry time for a shared access signature associated with this shared access policy.</span></span>
            </summary>
        <value><span data-ttu-id="b2116-112">Ein <see cref="T:System.DateTimeOffset" /> die Ablaufzeit der SAS angeben.</span><span class="sxs-lookup"><span data-stu-id="b2116-112">A <see cref="T:System.DateTimeOffset" /> specifying the shared access expiry time.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessStartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; SharedAccessStartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; SharedAccessStartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy.SharedAccessStartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessStartTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.SharedAccessStartTime : Nullable&lt;DateTimeOffset&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy.SharedAccessStartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b2116-113">Ruft ab oder legt die Startzeit für eine shared Access Signature, die mit dieser SAS-Richtlinie verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="b2116-113">Gets or sets the start time for a shared access signature associated with this shared access policy.</span></span>
            </summary>
        <value><span data-ttu-id="b2116-114">Ein <see cref="T:System.DateTimeOffset" /> Startzeit für den gemeinsamen Zugriff angibt.</span><span class="sxs-lookup"><span data-stu-id="b2116-114">A <see cref="T:System.DateTimeOffset" /> specifying the shared access start time.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>