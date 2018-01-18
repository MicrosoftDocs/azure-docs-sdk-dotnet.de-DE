<Type Name="DirectoryEntry" FullName="Microsoft.Azure.DataLake.Store.DirectoryEntry">
  <TypeSignature Language="C#" Value="public class DirectoryEntry" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DirectoryEntry extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.DataLake.Store.DirectoryEntry" />
  <TypeSignature Language="VB.NET" Value="Public Class DirectoryEntry" />
  <TypeSignature Language="F#" Value="type DirectoryEntry = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
    <AssemblyVersion>0.1.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9f9f5-101">Klasse, die die Metadaten der Verzeichniseintrag kapselt.</span><span class="sxs-lookup"><span data-stu-id="9f9f5-101">Class that encapsulates the metadata of the directory entry</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DirectoryEntry ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.DirectoryEntry.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9f9f5-102">Standardkonstruktor</span><span class="sxs-lookup"><span data-stu-id="9f9f5-102">Default constructor</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DirectoryEntry (string name, string fullName, long length, string group, string user, long lastAccessTime, long lastModifiedTime, string type, string permission, bool hasAcl, long expiryTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string fullName, int64 length, string group, string user, int64 lastAccessTime, int64 lastModifiedTime, string type, string permission, bool hasAcl, int64 expiryTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.DirectoryEntry.#ctor(System.String,System.String,System.Int64,System.String,System.String,System.Int64,System.Int64,System.String,System.String,System.Boolean,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, fullName As String, length As Long, group As String, user As String, lastAccessTime As Long, lastModifiedTime As Long, type As String, permission As String, hasAcl As Boolean, expiryTime As Long)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.DataLake.Store.DirectoryEntry : string * string * int64 * string * string * int64 * int64 * string * string * bool * int64 -&gt; Microsoft.Azure.DataLake.Store.DirectoryEntry" Usage="new Microsoft.Azure.DataLake.Store.DirectoryEntry (name, fullName, length, group, user, lastAccessTime, lastModifiedTime, type, permission, hasAcl, expiryTime)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="fullName" Type="System.String" />
        <Parameter Name="length" Type="System.Int64" />
        <Parameter Name="group" Type="System.String" />
        <Parameter Name="user" Type="System.String" />
        <Parameter Name="lastAccessTime" Type="System.Int64" />
        <Parameter Name="lastModifiedTime" Type="System.Int64" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="permission" Type="System.String" />
        <Parameter Name="hasAcl" Type="System.Boolean" />
        <Parameter Name="expiryTime" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="9f9f5-103">NAME</span><span class="sxs-lookup"><span data-stu-id="9f9f5-103">Name</span></span></param>
        <param name="fullName"><span data-ttu-id="9f9f5-104">Vollständiger Pfad</span><span class="sxs-lookup"><span data-stu-id="9f9f5-104">Full path</span></span></param>
        <param name="length"><span data-ttu-id="9f9f5-105">Größe der Datei</span><span class="sxs-lookup"><span data-stu-id="9f9f5-105">Size of file</span></span></param>
        <param name="group"><span data-ttu-id="9f9f5-106">Besitzer der Gruppe</span><span class="sxs-lookup"><span data-stu-id="9f9f5-106">Group owner</span></span></param>
        <param name="user"><span data-ttu-id="9f9f5-107">Benutzer Besitzer</span><span class="sxs-lookup"><span data-stu-id="9f9f5-107">User owner</span></span></param>
        <param name="lastAccessTime"><span data-ttu-id="9f9f5-108">Zeitpunkt des letzten Zugriffs als Millisekunden von 1/1/1970 abgerufen</span><span class="sxs-lookup"><span data-stu-id="9f9f5-108">Last access time obtained as milliseconds from 1/1/1970</span></span></param>
        <param name="lastModifiedTime"><span data-ttu-id="9f9f5-109">Uhrzeit der letzten Änderung als Millisekunden von 1/1/1970 abgerufen</span><span class="sxs-lookup"><span data-stu-id="9f9f5-109">Last modified time obtained as milliseconds from 1/1/1970</span></span></param>
        <param name="type"><span data-ttu-id="9f9f5-110">Datei oder eines Verzeichnisses</span><span class="sxs-lookup"><span data-stu-id="9f9f5-110">File or directory</span></span></param>
        <param name="permission"><span data-ttu-id="9f9f5-111">UNIX-Stil-Berechtigung</span><span class="sxs-lookup"><span data-stu-id="9f9f5-111">Unix style permission</span></span></param>
        <param name="hasAcl"><span data-ttu-id="9f9f5-112">Gibt an, ob die ACLs festgelegt sind</span><span class="sxs-lookup"><span data-stu-id="9f9f5-112">Whether ACLs are set</span></span></param>
        <param name="expiryTime"><span data-ttu-id="9f9f5-113">Uhrzeit, wann Datei ablaufen würde, als Millisekunden von 1/1/1970 abgerufen</span><span class="sxs-lookup"><span data-stu-id="9f9f5-113">Time when file would expire obtained as milliseconds from 1/1/1970</span></span></param>
        <summary>
            <span data-ttu-id="9f9f5-114">Konstruktor, jede Eigenschaft initialisiert.</span><span class="sxs-lookup"><span data-stu-id="9f9f5-114">Constructor that initializes each property</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpiryTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ExpiryTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ExpiryTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.DirectoryEntry.ExpiryTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpiryTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ExpiryTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.DataLake.Store.DirectoryEntry.ExpiryTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f9f5-115">Zeitpunkt, wenn die Datei abläuft</span><span class="sxs-lookup"><span data-stu-id="9f9f5-115">Instant when the file will expire</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FullName">
      <MemberSignature Language="C#" Value="public string FullName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FullName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.DirectoryEntry.FullName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FullName As String" />
      <MemberSignature Language="F#" Value="member this.FullName : string" Usage="Microsoft.Azure.DataLake.Store.DirectoryEntry.FullName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f9f5-116">Vollständiger Pfad des Verzeichniseintrags</span><span class="sxs-lookup"><span data-stu-id="9f9f5-116">Full Path of the directory entry</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Group">
      <MemberSignature Language="C#" Value="public string Group { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Group" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.DirectoryEntry.Group" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Group As String" />
      <MemberSignature Language="F#" Value="member this.Group : string" Usage="Microsoft.Azure.DataLake.Store.DirectoryEntry.Group" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f9f5-117">Besitzer der Gruppe der Datei oder des Verzeichnisses</span><span class="sxs-lookup"><span data-stu-id="9f9f5-117">Group owner of the file or directory</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HasAcl">
      <MemberSignature Language="C#" Value="public bool HasAcl { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool HasAcl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.DirectoryEntry.HasAcl" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HasAcl As Boolean" />
      <MemberSignature Language="F#" Value="member this.HasAcl : bool" Usage="Microsoft.Azure.DataLake.Store.DirectoryEntry.HasAcl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f9f5-118">Boolescher Wert, der angibt, ob die ACLs festgelegt werden</span><span class="sxs-lookup"><span data-stu-id="9f9f5-118">Boolean indicating whether ACLs are set</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastAccessTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastAccessTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastAccessTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.DirectoryEntry.LastAccessTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastAccessTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastAccessTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.DataLake.Store.DirectoryEntry.LastAccessTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f9f5-119">Zeitpunkt, wenn die Datei zuletzt verwendet wurden</span><span class="sxs-lookup"><span data-stu-id="9f9f5-119">Instant when the file was last accessed</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModifiedTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastModifiedTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastModifiedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.DirectoryEntry.LastModifiedTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModifiedTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastModifiedTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.DataLake.Store.DirectoryEntry.LastModifiedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f9f5-120">Zeitpunkt, wenn die Datei zuletzt geändert wurde</span><span class="sxs-lookup"><span data-stu-id="9f9f5-120">Instant when the file was last modified</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Length">
      <MemberSignature Language="C#" Value="public long Length { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Length" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.DirectoryEntry.Length" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Length As Long" />
      <MemberSignature Language="F#" Value="member this.Length : int64" Usage="Microsoft.Azure.DataLake.Store.DirectoryEntry.Length" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f9f5-121">Die Größe der Datei.</span><span class="sxs-lookup"><span data-stu-id="9f9f5-121">Size of the file.</span></span> <span data-ttu-id="9f9f5-122">0 (null) für Verzeichnis</span><span class="sxs-lookup"><span data-stu-id="9f9f5-122">Zero for directory</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.DirectoryEntry.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.DataLake.Store.DirectoryEntry.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f9f5-123">Name des Eintrags</span><span class="sxs-lookup"><span data-stu-id="9f9f5-123">Name of the entry</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Permission">
      <MemberSignature Language="C#" Value="public string Permission { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Permission" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.DirectoryEntry.Permission" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Permission As String" />
      <MemberSignature Language="F#" Value="member this.Permission : string" Usage="Microsoft.Azure.DataLake.Store.DirectoryEntry.Permission" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f9f5-124">Berechtigungszeichenfolge für UNIX-Stil</span><span class="sxs-lookup"><span data-stu-id="9f9f5-124">Unix style permission string</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.DataLake.Store.DirectoryEntryType Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.DataLake.Store.DirectoryEntryType Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.DirectoryEntry.Type" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Type As DirectoryEntryType" />
      <MemberSignature Language="F#" Value="member this.Type : Microsoft.Azure.DataLake.Store.DirectoryEntryType" Usage="Microsoft.Azure.DataLake.Store.DirectoryEntry.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.DataLake.Store.DirectoryEntryType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f9f5-125">Typ - Datei oder eines Verzeichnisses</span><span class="sxs-lookup"><span data-stu-id="9f9f5-125">Type- File or directory</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="User">
      <MemberSignature Language="C#" Value="public string User { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string User" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.DirectoryEntry.User" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property User As String" />
      <MemberSignature Language="F#" Value="member this.User : string" Usage="Microsoft.Azure.DataLake.Store.DirectoryEntry.User" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f9f5-126">Benutzer Besitzer der Datei oder des Verzeichnisses</span><span class="sxs-lookup"><span data-stu-id="9f9f5-126">User owner of the file or directory</span></span> 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>