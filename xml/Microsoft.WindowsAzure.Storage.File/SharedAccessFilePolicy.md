<Type Name="SharedAccessFilePolicy" FullName="Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy">
  <TypeSignature Language="C#" Value="public sealed class SharedAccessFilePolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SharedAccessFilePolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SharedAccessFilePolicy" />
  <TypeSignature Language="F#" Value="type SharedAccessFilePolicy = class" />
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
            <span data-ttu-id="a13ed-101">Stellt eine SAS-Richtlinie, die die Startzeit, Ablaufzeit und Berechtigungen für eine SAS angibt.</span><span class="sxs-lookup"><span data-stu-id="a13ed-101">Represents a shared access policy, which specifies the start time, expiry time, and permissions for a shared access signature.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedAccessFilePolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy.#ctor" />
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
            <span data-ttu-id="a13ed-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a13ed-102">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Permissions">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.File.SharedAccessFilePermissions Permissions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.File.SharedAccessFilePermissions Permissions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy.Permissions" />
      <MemberSignature Language="VB.NET" Value="Public Property Permissions As SharedAccessFilePermissions" />
      <MemberSignature Language="F#" Value="member this.Permissions : Microsoft.WindowsAzure.Storage.File.SharedAccessFilePermissions with get, set" Usage="Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy.Permissions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.File.SharedAccessFilePermissions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a13ed-103">Ruft ab oder legt die Berechtigungen für eine shared Access Signature, die mit dieser SAS-Richtlinie verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="a13ed-103">Gets or sets the permissions for a shared access signature associated with this shared access policy.</span></span>
            </summary>
        <value><span data-ttu-id="a13ed-104">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePermissions" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="a13ed-104">A <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePermissions" /> object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PermissionsFromString">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.File.SharedAccessFilePermissions PermissionsFromString (string input);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig valuetype Microsoft.WindowsAzure.Storage.File.SharedAccessFilePermissions PermissionsFromString(string input) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy.PermissionsFromString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function PermissionsFromString (input As String) As SharedAccessFilePermissions" />
      <MemberSignature Language="F#" Value="static member PermissionsFromString : string -&gt; Microsoft.WindowsAzure.Storage.File.SharedAccessFilePermissions" Usage="Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy.PermissionsFromString input" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.File.SharedAccessFilePermissions</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="input" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="input"><span data-ttu-id="a13ed-105">Die SAS-Berechtigungen im Zeichenfolgenformat.</span><span class="sxs-lookup"><span data-stu-id="a13ed-105">The shared access permissions, in string format.</span></span></param>
        <summary>
            <span data-ttu-id="a13ed-106">Erstellt eine <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePermissions" /> Objekt aus einer Berechtigungszeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="a13ed-106">Constructs a <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePermissions" /> object from a permissions string.</span></span>
            </summary>
        <returns><span data-ttu-id="a13ed-107">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePermissions" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="a13ed-107">A <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePermissions" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PermissionsToString">
      <MemberSignature Language="C#" Value="public static string PermissionsToString (Microsoft.WindowsAzure.Storage.File.SharedAccessFilePermissions permissions);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string PermissionsToString(valuetype Microsoft.WindowsAzure.Storage.File.SharedAccessFilePermissions permissions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy.PermissionsToString(Microsoft.WindowsAzure.Storage.File.SharedAccessFilePermissions)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function PermissionsToString (permissions As SharedAccessFilePermissions) As String" />
      <MemberSignature Language="F#" Value="static member PermissionsToString : Microsoft.WindowsAzure.Storage.File.SharedAccessFilePermissions -&gt; string" Usage="Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy.PermissionsToString permissions" />
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
        <Parameter Name="permissions" Type="Microsoft.WindowsAzure.Storage.File.SharedAccessFilePermissions" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="a13ed-108">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePermissions" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="a13ed-108">A <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePermissions" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="a13ed-109">Konvertiert die Berechtigungen für die SAS-Richtlinie in eine Zeichenfolge angegeben.</span><span class="sxs-lookup"><span data-stu-id="a13ed-109">Converts the permissions specified for the shared access policy to a string.</span></span>
            </summary>
        <returns><span data-ttu-id="a13ed-110">Die SAS-Berechtigungen im Zeichenfolgenformat.</span><span class="sxs-lookup"><span data-stu-id="a13ed-110">The shared access permissions, in string format.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessExpiryTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; SharedAccessExpiryTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; SharedAccessExpiryTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy.SharedAccessExpiryTime" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessExpiryTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.SharedAccessExpiryTime : Nullable&lt;DateTimeOffset&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy.SharedAccessExpiryTime" />
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
            <span data-ttu-id="a13ed-111">Ruft ab oder legt die Ablaufzeit für eine shared Access Signature, die mit dieser SAS-Richtlinie verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="a13ed-111">Gets or sets the expiry time for a shared access signature associated with this shared access policy.</span></span>
            </summary>
        <value><span data-ttu-id="a13ed-112">Ein <see cref="T:System.DateTimeOffset" /> die Ablaufzeit der SAS angeben.</span><span class="sxs-lookup"><span data-stu-id="a13ed-112">A <see cref="T:System.DateTimeOffset" /> specifying the shared access expiry time.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessStartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; SharedAccessStartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; SharedAccessStartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy.SharedAccessStartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessStartTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.SharedAccessStartTime : Nullable&lt;DateTimeOffset&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy.SharedAccessStartTime" />
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
            <span data-ttu-id="a13ed-113">Ruft ab oder legt die Startzeit für eine shared Access Signature, die mit dieser SAS-Richtlinie verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="a13ed-113">Gets or sets the start time for a shared access signature associated with this shared access policy.</span></span>
            </summary>
        <value><span data-ttu-id="a13ed-114">Ein <see cref="T:System.DateTimeOffset" /> Startzeit für den gemeinsamen Zugriff angibt.</span><span class="sxs-lookup"><span data-stu-id="a13ed-114">A <see cref="T:System.DateTimeOffset" /> specifying the shared access start time.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>