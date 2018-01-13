<Type Name="StartTask" FullName="Microsoft.Azure.Management.Batch.Models.StartTask">
  <TypeSignature Language="C#" Value="public class StartTask" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StartTask extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.StartTask" />
  <TypeSignature Language="VB.NET" Value="Public Class StartTask" />
  <TypeSignature Language="F#" Value="type StartTask = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="68f59-101">Eine Aufgabe, die ausgeführt wird, wenn ein Serverknoten einen Pool in der Azure Batch-Dienst verknüpft, oder der Computeknoten neu gestartet, oder ein reimaging ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="68f59-101">A task which is run when a compute node joins a pool in the Azure Batch service, or when the compute node is rebooted or reimaged.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StartTask ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.StartTask.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="68f59-102">Initialisiert eine neue Instanz der StartTask-Klasse.</span><span class="sxs-lookup"><span data-stu-id="68f59-102">Initializes a new instance of the StartTask class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StartTask (string commandLine = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ResourceFile&gt; resourceFiles = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.EnvironmentSetting&gt; environmentSettings = null, Microsoft.Azure.Management.Batch.Models.UserIdentity userIdentity = null, Nullable&lt;int&gt; maxTaskRetryCount = null, Nullable&lt;bool&gt; waitForSuccess = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string commandLine, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.ResourceFile&gt; resourceFiles, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.EnvironmentSetting&gt; environmentSettings, class Microsoft.Azure.Management.Batch.Models.UserIdentity userIdentity, valuetype System.Nullable`1&lt;int32&gt; maxTaskRetryCount, valuetype System.Nullable`1&lt;bool&gt; waitForSuccess) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.StartTask.#ctor(System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Batch.Models.ResourceFile},System.Collections.Generic.IList{Microsoft.Azure.Management.Batch.Models.EnvironmentSetting},Microsoft.Azure.Management.Batch.Models.UserIdentity,System.Nullable{System.Int32},System.Nullable{System.Boolean})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.StartTask : string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ResourceFile&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.EnvironmentSetting&gt; * Microsoft.Azure.Management.Batch.Models.UserIdentity * Nullable&lt;int&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.Batch.Models.StartTask" Usage="new Microsoft.Azure.Management.Batch.Models.StartTask (commandLine, resourceFiles, environmentSettings, userIdentity, maxTaskRetryCount, waitForSuccess)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="commandLine" Type="System.String" />
        <Parameter Name="resourceFiles" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ResourceFile&gt;" />
        <Parameter Name="environmentSettings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.EnvironmentSetting&gt;" />
        <Parameter Name="userIdentity" Type="Microsoft.Azure.Management.Batch.Models.UserIdentity" />
        <Parameter Name="maxTaskRetryCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="waitForSuccess" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="commandLine"><span data-ttu-id="68f59-103">Die Befehlszeile der Startaufgabe.</span><span class="sxs-lookup"><span data-stu-id="68f59-103">The command line of the start task.</span></span></param>
        <param name="resourceFiles"><span data-ttu-id="68f59-104">Eine Liste der Dateien, die der Batch-Dienst vor dem Ausführen der Befehlszeile mit dem Computeknoten heruntergeladen wird.</span><span class="sxs-lookup"><span data-stu-id="68f59-104">A list of files that the Batch service will download to the compute node before running the command line.</span></span></param>
        <param name="environmentSettings"><span data-ttu-id="68f59-105">Eine Liste von umgebungsvariableneinstellungen für die Startaufgabe auszuführen.</span><span class="sxs-lookup"><span data-stu-id="68f59-105">A list of environment variable settings for the start task.</span></span></param>
        <param name="userIdentity"><span data-ttu-id="68f59-106">Die Benutzeridentität, unter der die Startaufgabe ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="68f59-106">The user identity under which the start task runs.</span></span></param>
        <param name="maxTaskRetryCount"><span data-ttu-id="68f59-107">Gibt an, wie oft der Task maximal wiederholt werden kann.</span><span class="sxs-lookup"><span data-stu-id="68f59-107">The maximum number of times the task may be retried.</span></span></param>
        <param name="waitForSuccess"><span data-ttu-id="68f59-108">Gibt an, ob der Batch-Dienst warten soll, für die Startaufgabe erfolgreich abgeschlossen (d. h. mit Exitcode 0 beendet) vor dem Planen alle Aufgaben auf den Computeknoten.</span><span class="sxs-lookup"><span data-stu-id="68f59-108">Whether the Batch service should wait for the start task to complete successfully (that is, to exit with exit code 0) before scheduling any tasks on the compute node.</span></span></param>
        <summary>
            <span data-ttu-id="68f59-109">Initialisiert eine neue Instanz der StartTask-Klasse.</span><span class="sxs-lookup"><span data-stu-id="68f59-109">Initializes a new instance of the StartTask class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommandLine">
      <MemberSignature Language="C#" Value="public string CommandLine { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CommandLine" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.StartTask.CommandLine" />
      <MemberSignature Language="VB.NET" Value="Public Property CommandLine As String" />
      <MemberSignature Language="F#" Value="member this.CommandLine : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.StartTask.CommandLine" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="commandLine")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="68f59-110">Ruft ab oder legt die Befehlszeile des Startaufgabe.</span><span class="sxs-lookup"><span data-stu-id="68f59-110">Gets or sets the command line of the start task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="68f59-111">Die Befehlszeile wird nicht unter einer Shell ausgeführt, und daher kann nicht nutzen Shell-Funktionen, z. B. umgebungsvariablenerweiterung.</span><span class="sxs-lookup"><span data-stu-id="68f59-111">The command line does not run under a shell, and therefore cannot take advantage of shell features such as environment variable expansion.</span></span> <span data-ttu-id="68f59-112">Wenn Sie solche Funktionen nutzen möchten, Sie sollten rufen Sie die Befehlsshell in der Befehlszeile z. B. mit "Cmd/c MyCommand" in Windows oder "/ Bin/sh - C MyCommand" unter Linux.</span><span class="sxs-lookup"><span data-stu-id="68f59-112">If you want to take advantage of such features, you should invoke the shell in the command line, for example using "cmd /c MyCommand" in Windows or "/bin/sh -c MyCommand" in Linux.</span></span>
            <span data-ttu-id="68f59-113">Erforderlich, wenn alle anderen Eigenschaften für den StartTask angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="68f59-113">Required if any other properties of the startTask are specified.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvironmentSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.EnvironmentSetting&gt; EnvironmentSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.EnvironmentSetting&gt; EnvironmentSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.StartTask.EnvironmentSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property EnvironmentSettings As IList(Of EnvironmentSetting)" />
      <MemberSignature Language="F#" Value="member this.EnvironmentSettings : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.EnvironmentSetting&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.StartTask.EnvironmentSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="environmentSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.EnvironmentSetting&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="68f59-114">Ruft ab oder legt eine Liste von umgebungsvariableneinstellungen für die Startaufgabe auszuführen.</span><span class="sxs-lookup"><span data-stu-id="68f59-114">Gets or sets a list of environment variable settings for the start task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxTaskRetryCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxTaskRetryCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxTaskRetryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.StartTask.MaxTaskRetryCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxTaskRetryCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxTaskRetryCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.StartTask.MaxTaskRetryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxTaskRetryCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="68f59-115">Ruft ab oder legt die maximale Anzahl der Häufigkeit, mit die der Vorgang wiederholt werden kann.</span><span class="sxs-lookup"><span data-stu-id="68f59-115">Gets or sets the maximum number of times the task may be retried.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="68f59-116">Der Batch-Dienst wiederholt einen Task, wenn sein Exitcode ungleich null ist.</span><span class="sxs-lookup"><span data-stu-id="68f59-116">The Batch service retries a task if its exit code is nonzero.</span></span> <span data-ttu-id="68f59-117">Beachten Sie, dass dieser Wert die Anzahl der Wiederholungen ausdrücklich steuert.</span><span class="sxs-lookup"><span data-stu-id="68f59-117">Note that this value specifically controls the number of retries.</span></span> <span data-ttu-id="68f59-118">Der Batch-Dienst wiederholt den Task einmal und kann ihn anschließend bis zu diesem Grenzwert wiederholen.</span><span class="sxs-lookup"><span data-stu-id="68f59-118">The Batch service will try the task once, and may then retry up to this limit.</span></span> <span data-ttu-id="68f59-119">Beispielsweise ist die maximale Anzahl von Wiederholungsversuchen 3, Batch versucht die Aufgabe bis zu 4 Mal (einen ersten Versuch und 3 Wiederholungen).</span><span class="sxs-lookup"><span data-stu-id="68f59-119">For example, if the maximum retry count is 3, Batch tries the task up to 4 times (one initial try and 3 retries).</span></span> <span data-ttu-id="68f59-120">Wenn die maximale Anzahl von Wiederholungsversuchen 0 ist, wird der Batch-Dienst nicht die Aufgabe erneut versucht.</span><span class="sxs-lookup"><span data-stu-id="68f59-120">If the maximum retry count is 0, the Batch service does not retry the task.</span></span> <span data-ttu-id="68f59-121">Wenn die maximale Anzahl wiederholen ist-1, die Batch-Dienst Wiederholungen der Task unbegrenzt.</span><span class="sxs-lookup"><span data-stu-id="68f59-121">If the maximum retry count is -1, the Batch service retries the task without limit.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceFiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ResourceFile&gt; ResourceFiles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.ResourceFile&gt; ResourceFiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.StartTask.ResourceFiles" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceFiles As IList(Of ResourceFile)" />
      <MemberSignature Language="F#" Value="member this.ResourceFiles : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ResourceFile&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.StartTask.ResourceFiles" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceFiles")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ResourceFile&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="68f59-122">Ruft ab oder legt eine Liste der Dateien, die der Batch-Dienst auf den Serverknoten herunterlädt, vor dem Ausführen der Befehlszeile.</span><span class="sxs-lookup"><span data-stu-id="68f59-122">Gets or sets a list of files that the Batch service will download to the compute node before running the command line.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserIdentity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.UserIdentity UserIdentity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.UserIdentity UserIdentity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.StartTask.UserIdentity" />
      <MemberSignature Language="VB.NET" Value="Public Property UserIdentity As UserIdentity" />
      <MemberSignature Language="F#" Value="member this.UserIdentity : Microsoft.Azure.Management.Batch.Models.UserIdentity with get, set" Usage="Microsoft.Azure.Management.Batch.Models.StartTask.UserIdentity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="userIdentity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.UserIdentity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="68f59-123">Ruft ab oder legt die Identität des Benutzers, unter der die Startaufgabe ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="68f59-123">Gets or sets the user identity under which the start task runs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="68f59-124">Wenn nicht angegeben, der Task als Nichtadministrator-eindeutige Benutzer an die Aufgabe ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="68f59-124">If omitted, the task runs as a non-administrative user unique to the task.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="WaitForSuccess">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; WaitForSuccess { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; WaitForSuccess" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.StartTask.WaitForSuccess" />
      <MemberSignature Language="VB.NET" Value="Public Property WaitForSuccess As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.WaitForSuccess : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.StartTask.WaitForSuccess" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="waitForSuccess")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="68f59-125">Ruft ab oder legt sie fest, ob der Batch-Dienst warten soll, für die Startaufgabe erfolgreich abgeschlossen (d. h. mit Exitcode 0 beendet) vor dem Planen alle Aufgaben auf den Computeknoten.</span><span class="sxs-lookup"><span data-stu-id="68f59-125">Gets or sets whether the Batch service should wait for the start task to complete successfully (that is, to exit with exit code 0) before scheduling any tasks on the compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="68f59-126">Wenn "true" und die Startaufgabe nicht auf einem Serverknoten, wiederholt der Batch-Dienst die Startaufgabe die maximale Anzahl von Wiederholungsversuchen ("maxtaskretrycount").</span><span class="sxs-lookup"><span data-stu-id="68f59-126">If true and the start task fails on a compute node, the Batch service retries the start task up to its maximum retry count (maxTaskRetryCount).</span></span> <span data-ttu-id="68f59-127">Wenn der Vorgang hat immer noch nicht erfolgreich abgeschlossen wurde nach aller Wiederholungsversuche, und klicken Sie dann auf die Batch-Dienst-Markierungen den Compute-Knoten kann nicht verwendet werden und wird nicht Planen von Aufgaben.</span><span class="sxs-lookup"><span data-stu-id="68f59-127">If the task has still not completed successfully after all retries, then the Batch service marks the compute node unusable, and will not schedule tasks to it.</span></span> <span data-ttu-id="68f59-128">Diese Bedingung kann über das Knotenstatus und Planung Fehlerdetail erkannt werden.</span><span class="sxs-lookup"><span data-stu-id="68f59-128">This condition can be detected via the node state and scheduling error detail.</span></span> <span data-ttu-id="68f59-129">Wenn "false", wartet der Batch-Dienst nicht für die Startaufgabe abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="68f59-129">If false, the Batch service will not wait for the start task to complete.</span></span> <span data-ttu-id="68f59-130">In diesem Fall können andere Aufgaben starten, auf dem Computeknoten ausgeführt werden, während die Startaufgabe ausgeführt wird; und auch wenn die Startaufgabe ein Fehler auftritt, neue Aufgaben weiterhin auf dem Knoten geplant werden.</span><span class="sxs-lookup"><span data-stu-id="68f59-130">In this case, other tasks can start executing on the compute node while the start task is still running; and even if the start task fails, new tasks will continue to be scheduled on the node.</span></span> <span data-ttu-id="68f59-131">Der Standardwert ist false.</span><span class="sxs-lookup"><span data-stu-id="68f59-131">The default is false.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>