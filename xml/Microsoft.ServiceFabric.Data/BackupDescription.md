<Type Name="BackupDescription" FullName="Microsoft.ServiceFabric.Data.BackupDescription">
  <TypeSignature Language="C#" Value="public struct BackupDescription" />
  <TypeSignature Language="ILAsm" Value=".class public sequential ansi sealed beforefieldinit BackupDescription extends System.ValueType" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.BackupDescription" />
  <TypeSignature Language="VB.NET" Value="Public Structure BackupDescription" />
  <TypeSignature Language="F#" Value="type BackupDescription = struct" />
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
            <span data-ttu-id="e1b2c-101">Eine BackupDescription enthält alle Informationen zum Sichern eines zustandsbehafteten dienstreplikats erforderlich.</span><span class="sxs-lookup"><span data-stu-id="e1b2c-101">A BackupDescription contains all of the information necessary to backup a stateful service replica.</span></span> 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupDescription (Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;bool&gt;&gt; backupCallback);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Func`3&lt;class Microsoft.ServiceFabric.Data.BackupInfo, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; backupCallback) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.BackupDescription.#ctor(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (backupCallback As Func(Of BackupInfo, CancellationToken, Task(Of Boolean)))" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.BackupDescription : Func&lt;Microsoft.ServiceFabric.Data.BackupInfo, System.Threading.CancellationToken, System.Threading.Tasks.Task&lt;bool&gt;&gt; -&gt; Microsoft.ServiceFabric.Data.BackupDescription" Usage="new Microsoft.ServiceFabric.Data.BackupDescription backupCallback" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="backupCallback" Type="System.Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;System.Boolean&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="backupCallback">
            <span data-ttu-id="e1b2c-102">Rückruf, der aufgerufen wird, wenn sich der Sicherungsordner erstellt und lokal vom System aufgefüllt wurde.</span><span class="sxs-lookup"><span data-stu-id="e1b2c-102">Callback to be called when the backup folder has been created and populated locally by the system.</span></span> <span data-ttu-id="e1b2c-103">Dieser Ordner kann jetzt aus dem Knoten verschoben werden.</span><span class="sxs-lookup"><span data-stu-id="e1b2c-103">This folder is now ready to be moved out of the node.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e1b2c-104">Initialisiert eine neue Instanz der <cref name="BackupDescription" />-Struktur.</span><span class="sxs-lookup"><span data-stu-id="e1b2c-104">Initializes a new instance of the <cref name="BackupDescription" /> structure.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupDescription (Microsoft.ServiceFabric.Data.BackupOption option, Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;bool&gt;&gt; backupCallback);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.ServiceFabric.Data.BackupOption option, class System.Func`3&lt;class Microsoft.ServiceFabric.Data.BackupInfo, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; backupCallback) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.BackupDescription.#ctor(Microsoft.ServiceFabric.Data.BackupOption,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (option As BackupOption, backupCallback As Func(Of BackupInfo, CancellationToken, Task(Of Boolean)))" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.BackupDescription : Microsoft.ServiceFabric.Data.BackupOption * Func&lt;Microsoft.ServiceFabric.Data.BackupInfo, System.Threading.CancellationToken, System.Threading.Tasks.Task&lt;bool&gt;&gt; -&gt; Microsoft.ServiceFabric.Data.BackupDescription" Usage="new Microsoft.ServiceFabric.Data.BackupDescription (option, backupCallback)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="option" Type="Microsoft.ServiceFabric.Data.BackupOption" />
        <Parameter Name="backupCallback" Type="System.Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;System.Boolean&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="option">
            <span data-ttu-id="e1b2c-105">Die <cref name="BackupOption" /> für die Sicherung.</span><span class="sxs-lookup"><span data-stu-id="e1b2c-105">The <cref name="BackupOption" /> for the backup.</span></span>
            </param>
        <param name="backupCallback">
            <span data-ttu-id="e1b2c-106">Rückruf, der aufgerufen wird, wenn sich der Sicherungsordner lokal erstellt wurde, und kann jetzt aus dem Knoten verschoben werden.</span><span class="sxs-lookup"><span data-stu-id="e1b2c-106">Callback to be called when the backup folder has been created locally and is ready to be moved out of the node.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e1b2c-107">Initialisiert eine neue Instanz der <cref name="BackupDescription" />-Struktur.</span><span class="sxs-lookup"><span data-stu-id="e1b2c-107">Initializes a new instance of the <cref name="BackupDescription" /> structure.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupCallback">
      <MemberSignature Language="C#" Value="public Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;bool&gt;&gt; BackupCallback { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`3&lt;class Microsoft.ServiceFabric.Data.BackupInfo, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; BackupCallback" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.BackupDescription.BackupCallback" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupCallback As Func(Of BackupInfo, CancellationToken, Task(Of Boolean))" />
      <MemberSignature Language="F#" Value="member this.BackupCallback : Func&lt;Microsoft.ServiceFabric.Data.BackupInfo, System.Threading.CancellationToken, System.Threading.Tasks.Task&lt;bool&gt;&gt;" Usage="Microsoft.ServiceFabric.Data.BackupDescription.BackupCallback" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;System.Boolean&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e1b2c-108">Ruft ab, der Rückruf, der aufgerufen wird, wenn sich der Sicherungsordner lokal erstellt wurde, und kann jetzt aus dem Knoten verschoben werden.</span><span class="sxs-lookup"><span data-stu-id="e1b2c-108">Gets the callback to be called when the backup folder has been created locally and is ready to be moved out of the node.</span></span>
            </summary>
        <value>
            <span data-ttu-id="e1b2c-109">Die Sicherung Rückruffunktion, die häufig verwendet, um den Sicherungsordner in einem externen Speicherort zu kopieren.</span><span class="sxs-lookup"><span data-stu-id="e1b2c-109">The backup callback function commonly used to copy the backup folder to an external location.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="e1b2c-110">Backup Rückruffunktion nimmt in einem BackupInfo und der Abbruch und gibt eine Aufgabe, die Verarbeitung von Sicherungsordner darstellt.</span><span class="sxs-lookup"><span data-stu-id="e1b2c-110">Backup callback function takes in BackupInfo and Cancellation token and returns a Task that represents the processing of the backup folder.</span></span>
            <span data-ttu-id="e1b2c-111">Boolescher Wert zurückgegeben, die für die BackupCallback Geben Sie an, ob der Dienst konnte erfolgreich den Sicherungsordner in einem externen Speicherort zu verschieben.</span><span class="sxs-lookup"><span data-stu-id="e1b2c-111">Boolean returned by the backupCallback indicate whether the service was able to successfully move the backup folder to an external location.</span></span>
            <span data-ttu-id="e1b2c-112">Wenn "false" zurückgegeben wird, löst BackupAsync InvalidOperationException aus der entsprechenden Fehlermeldung BackupCallback "false" zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="e1b2c-112">If false is returned, BackupAsync throws InvalidOperationException with the relevant message indicating backupCallback returned false.</span></span>
            <span data-ttu-id="e1b2c-113">Darüber hinaus wird Sicherung als fehlgeschlagen markiert.</span><span class="sxs-lookup"><span data-stu-id="e1b2c-113">Also, backup will be marked as unsuccessful.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Option">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Data.BackupOption Option { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Data.BackupOption Option" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.BackupDescription.Option" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Option As BackupOption" />
      <MemberSignature Language="F#" Value="member this.Option : Microsoft.ServiceFabric.Data.BackupOption" Usage="Microsoft.ServiceFabric.Data.BackupDescription.Option" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.BackupOption</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e1b2c-114">Der Typ der Sicherung ausführen.</span><span class="sxs-lookup"><span data-stu-id="e1b2c-114">The type of backup to perform.</span></span>
            </summary>
        <value>
            <span data-ttu-id="e1b2c-115">Der Typ der Sicherung.</span><span class="sxs-lookup"><span data-stu-id="e1b2c-115">The type of the backup.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>