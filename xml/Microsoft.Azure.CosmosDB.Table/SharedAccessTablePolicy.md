<Type Name="SharedAccessTablePolicy" FullName="Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy">
  <TypeSignature Language="C#" Value="public sealed class SharedAccessTablePolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SharedAccessTablePolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SharedAccessTablePolicy" />
  <TypeSignature Language="F#" Value="type SharedAccessTablePolicy = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8a563-101">Stellt eine SAS-Richtlinie, die die Startzeit, Ablaufzeit und Berechtigungen für eine SAS angibt.</span><span class="sxs-lookup"><span data-stu-id="8a563-101">Represents a shared access policy, which specifies the start time, expiry time, and permissions for a shared access signature.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedAccessTablePolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8a563-102">Initialisiert eine neue Instanz der SharedAccessTablePolicy-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8a563-102">Initializes a new instance of the SharedAccessTablePolicy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Permissions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.CosmosDB.Table.SharedAccessTablePermissions Permissions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.CosmosDB.Table.SharedAccessTablePermissions Permissions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy.Permissions" />
      <MemberSignature Language="VB.NET" Value="Public Property Permissions As SharedAccessTablePermissions" />
      <MemberSignature Language="F#" Value="member this.Permissions : Microsoft.Azure.CosmosDB.Table.SharedAccessTablePermissions with get, set" Usage="Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy.Permissions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.SharedAccessTablePermissions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8a563-103">Ruft ab oder legt die Berechtigungen für eine shared Access Signature, die mit dieser SAS-Richtlinie verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="8a563-103">Gets or sets the permissions for a shared access signature associated with this shared access policy.</span></span>
            </summary>
        <value><span data-ttu-id="8a563-104">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.SharedAccessTablePermissions" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="8a563-104">A <see cref="T:Microsoft.Azure.CosmosDB.Table.SharedAccessTablePermissions" /> object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PermissionsFromString">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.CosmosDB.Table.SharedAccessTablePermissions PermissionsFromString (string input);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig valuetype Microsoft.Azure.CosmosDB.Table.SharedAccessTablePermissions PermissionsFromString(string input) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy.PermissionsFromString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function PermissionsFromString (input As String) As SharedAccessTablePermissions" />
      <MemberSignature Language="F#" Value="static member PermissionsFromString : string -&gt; Microsoft.Azure.CosmosDB.Table.SharedAccessTablePermissions" Usage="Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy.PermissionsFromString input" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.SharedAccessTablePermissions</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="input" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="input"><span data-ttu-id="8a563-105">Die SAS-Berechtigungen im Zeichenfolgenformat.</span><span class="sxs-lookup"><span data-stu-id="8a563-105">The shared access permissions in string format.</span></span></param>
        <summary>
            <span data-ttu-id="8a563-106">Erstellt eine <see cref="T:Microsoft.Azure.CosmosDB.Table.SharedAccessTablePermissions" /> Objekt aus einer Berechtigungszeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="8a563-106">Constructs a <see cref="T:Microsoft.Azure.CosmosDB.Table.SharedAccessTablePermissions" /> object from a permissions string.</span></span>
            </summary>
        <returns><span data-ttu-id="8a563-107">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.SharedAccessTablePermissions" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="8a563-107">A <see cref="T:Microsoft.Azure.CosmosDB.Table.SharedAccessTablePermissions" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PermissionsToString">
      <MemberSignature Language="C#" Value="public static string PermissionsToString (Microsoft.Azure.CosmosDB.Table.SharedAccessTablePermissions permissions);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string PermissionsToString(valuetype Microsoft.Azure.CosmosDB.Table.SharedAccessTablePermissions permissions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy.PermissionsToString(Microsoft.Azure.CosmosDB.Table.SharedAccessTablePermissions)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function PermissionsToString (permissions As SharedAccessTablePermissions) As String" />
      <MemberSignature Language="F#" Value="static member PermissionsToString : Microsoft.Azure.CosmosDB.Table.SharedAccessTablePermissions -&gt; string" Usage="Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy.PermissionsToString permissions" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissions" Type="Microsoft.Azure.CosmosDB.Table.SharedAccessTablePermissions" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="8a563-108">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.SharedAccessTablePermissions" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="8a563-108">A <see cref="T:Microsoft.Azure.CosmosDB.Table.SharedAccessTablePermissions" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="8a563-109">Konvertiert die Berechtigungen für die SAS-Richtlinie in eine Zeichenfolge angegeben.</span><span class="sxs-lookup"><span data-stu-id="8a563-109">Converts the permissions specified for the shared access policy to a string.</span></span>
            </summary>
        <returns><span data-ttu-id="8a563-110">Die SAS-Berechtigungen im Zeichenfolgenformat.</span><span class="sxs-lookup"><span data-stu-id="8a563-110">The shared access permissions in string format.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessExpiryTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; SharedAccessExpiryTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; SharedAccessExpiryTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy.SharedAccessExpiryTime" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessExpiryTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.SharedAccessExpiryTime : Nullable&lt;DateTimeOffset&gt; with get, set" Usage="Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy.SharedAccessExpiryTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8a563-111">Ruft ab oder legt die Ablaufzeit für eine shared Access Signature, die mit dieser SAS-Richtlinie verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="8a563-111">Gets or sets the expiry time for a shared access signature associated with this shared access policy.</span></span>
            </summary>
        <value><span data-ttu-id="8a563-112">Ein <see cref="T:System.DateTimeOffset" /> die Ablaufzeit der SAS angeben.</span><span class="sxs-lookup"><span data-stu-id="8a563-112">A <see cref="T:System.DateTimeOffset" /> specifying the shared access expiry time.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessStartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; SharedAccessStartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; SharedAccessStartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy.SharedAccessStartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessStartTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.SharedAccessStartTime : Nullable&lt;DateTimeOffset&gt; with get, set" Usage="Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy.SharedAccessStartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8a563-113">Ruft ab oder legt die Startzeit für eine shared Access Signature, die mit dieser SAS-Richtlinie verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="8a563-113">Gets or sets the start time for a shared access signature associated with this shared access policy.</span></span>
            </summary>
        <value><span data-ttu-id="8a563-114">Ein <see cref="T:System.DateTimeOffset" /> Startzeit für den gemeinsamen Zugriff angibt.</span><span class="sxs-lookup"><span data-stu-id="8a563-114">A <see cref="T:System.DateTimeOffset" /> specifying the shared access start time.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>