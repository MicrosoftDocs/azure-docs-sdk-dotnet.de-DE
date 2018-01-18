<Type Name="RestoreDescription" FullName="Microsoft.ServiceFabric.Data.RestoreDescription">
  <TypeSignature Language="C#" Value="public struct RestoreDescription" />
  <TypeSignature Language="ILAsm" Value=".class public sequential ansi sealed beforefieldinit RestoreDescription extends System.ValueType" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.RestoreDescription" />
  <TypeSignature Language="VB.NET" Value="Public Structure RestoreDescription" />
  <TypeSignature Language="F#" Value="type RestoreDescription = struct" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ValueType</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="fbe66-101">Eine RestoreDescription enthält alle Informationen, die zum Wiederherstellen eines zustandsbehafteten dienstreplikats erforderlich.</span><span class="sxs-lookup"><span data-stu-id="fbe66-101">A RestoreDescription contains all of the information necessary to restore a stateful service replica.</span></span> 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RestoreDescription (string backupFolderPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string backupFolderPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.RestoreDescription.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (backupFolderPath As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.RestoreDescription : string -&gt; Microsoft.ServiceFabric.Data.RestoreDescription" Usage="new Microsoft.ServiceFabric.Data.RestoreDescription backupFolderPath" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="backupFolderPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="backupFolderPath">
            <span data-ttu-id="fbe66-102">Das Verzeichnis, in dem das Replikat aus wiederhergestellt werden.</span><span class="sxs-lookup"><span data-stu-id="fbe66-102">The directory where the replica is to be restored from.</span></span>
            <span data-ttu-id="fbe66-103">Dieser Parameter kann nicht null, leer oder nur aus Leerzeichen bestehen.</span><span class="sxs-lookup"><span data-stu-id="fbe66-103">This parameter cannot be null, empty, or consist only of whitespace.</span></span> <span data-ttu-id="fbe66-104">UNC-Pfade können auch angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="fbe66-104">UNC paths may also be provided.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fbe66-105">Initialisiert eine neue Instanz der dem <cref name="RestoreDescription" /> Struktur</span><span class="sxs-lookup"><span data-stu-id="fbe66-105">Initializes a new instance of the <cref name="RestoreDescription" /> structure</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RestoreDescription (string backupFolderPath, Microsoft.ServiceFabric.Data.RestorePolicy restorePolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string backupFolderPath, valuetype Microsoft.ServiceFabric.Data.RestorePolicy restorePolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.RestoreDescription.#ctor(System.String,Microsoft.ServiceFabric.Data.RestorePolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.RestoreDescription : string * Microsoft.ServiceFabric.Data.RestorePolicy -&gt; Microsoft.ServiceFabric.Data.RestoreDescription" Usage="new Microsoft.ServiceFabric.Data.RestoreDescription (backupFolderPath, restorePolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="backupFolderPath" Type="System.String" />
        <Parameter Name="restorePolicy" Type="Microsoft.ServiceFabric.Data.RestorePolicy" />
      </Parameters>
      <Docs>
        <param name="backupFolderPath">
            <span data-ttu-id="fbe66-106">Das Verzeichnis, in dem das Replikat aus wiederhergestellt werden.</span><span class="sxs-lookup"><span data-stu-id="fbe66-106">The directory where the replica is to be restored from.</span></span>
            <span data-ttu-id="fbe66-107">Dieser Parameter kann nicht null, leer oder nur aus Leerzeichen bestehen.</span><span class="sxs-lookup"><span data-stu-id="fbe66-107">This parameter cannot be null, empty, or consist only of whitespace.</span></span> <span data-ttu-id="fbe66-108">UNC-Pfade können auch angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="fbe66-108">UNC paths may also be provided.</span></span>
            </param>
        <param name="restorePolicy"><span data-ttu-id="fbe66-109">Die Richtlinie für die Wiederherstellung.</span><span class="sxs-lookup"><span data-stu-id="fbe66-109">The restore policy.</span></span></param>
        <summary>
            <span data-ttu-id="fbe66-110">Initialisiert eine neue Instanz der RestoreDescription-Struktur.</span><span class="sxs-lookup"><span data-stu-id="fbe66-110">Initializes a new instance of the RestoreDescription structure.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupFolderPath">
      <MemberSignature Language="C#" Value="public string BackupFolderPath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackupFolderPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.RestoreDescription.BackupFolderPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupFolderPath As String" />
      <MemberSignature Language="F#" Value="member this.BackupFolderPath : string" Usage="Microsoft.ServiceFabric.Data.RestoreDescription.BackupFolderPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fbe66-111">Ruft das Verzeichnis, das wiederherzustellenden Zustand des Replikats verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="fbe66-111">Gets the directory which will be used to restore the replica's state.</span></span>
            <span data-ttu-id="fbe66-112">Dieser Parameter kann nicht null, leer oder nur aus Leerzeichen bestehen.</span><span class="sxs-lookup"><span data-stu-id="fbe66-112">This parameter cannot be null, empty, or consist only of whitespace.</span></span> <span data-ttu-id="fbe66-113">UNC-Pfade können auch angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="fbe66-113">UNC paths may also be provided.</span></span>
            </summary>
        <value>
            <span data-ttu-id="fbe66-114">Das Verzeichnis der verwendet wird, um den Status für das Replikat wiederherzustellen.</span><span class="sxs-lookup"><span data-stu-id="fbe66-114">The directory which will be used to restore the replica's state.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="fbe66-115">Ordner muss über mindestens eine vollständige Sicherung enthalten.</span><span class="sxs-lookup"><span data-stu-id="fbe66-115">Folder must at least contain one full backup.</span></span>
            <span data-ttu-id="fbe66-116">Darüber hinaus kann es eine oder mehrere inkrementelle Sicherungen enthalten.</span><span class="sxs-lookup"><span data-stu-id="fbe66-116">In addition, it could include one or more incremental backups.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Policy">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Data.RestorePolicy Policy { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Data.RestorePolicy Policy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.RestoreDescription.Policy" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Policy As RestorePolicy" />
      <MemberSignature Language="F#" Value="member this.Policy : Microsoft.ServiceFabric.Data.RestorePolicy" Usage="Microsoft.ServiceFabric.Data.RestoreDescription.Policy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.RestorePolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fbe66-117">Ruft die Richtlinie für die Wiederherstellung an.</span><span class="sxs-lookup"><span data-stu-id="fbe66-117">Gets the restore policy.</span></span>
            </summary>
        <value>
            <span data-ttu-id="fbe66-118">Richtlinie für die Wiederherstellung verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="fbe66-118">Policy to be used for the restore.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>