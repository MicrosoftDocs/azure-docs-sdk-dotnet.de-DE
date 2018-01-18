<Type Name="MultiInstanceSettings" FullName="Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings">
  <TypeSignature Language="C#" Value="public class MultiInstanceSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MultiInstanceSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class MultiInstanceSettings" />
  <TypeSignature Language="F#" Value="type MultiInstanceSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0a9d7-101">Einstellungen auf, die angeben, wie eine Aufgabe mit mehreren Instanzen ausgeführt werden soll.</span><span class="sxs-lookup"><span data-stu-id="0a9d7-101">Settings which specify how to run a multi-instance task.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="0a9d7-102">Mit mehreren Instanzen Tasks werden häufig verwendet, um MPI-Aufgaben zu unterstützen.</span><span class="sxs-lookup"><span data-stu-id="0a9d7-102">Multi-instance tasks are commonly used to support MPI tasks.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiInstanceSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0a9d7-103">Initialisiert eine neue Instanz der MultiInstanceSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0a9d7-103">Initializes a new instance of the MultiInstanceSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiInstanceSettings (string coordinationCommandLine, Nullable&lt;int&gt; numberOfInstances = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; commonResourceFiles = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string coordinationCommandLine, valuetype System.Nullable`1&lt;int32&gt; numberOfInstances, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; commonResourceFiles) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings.#ctor(System.String,System.Nullable{System.Int32},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ResourceFile})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (coordinationCommandLine As String, Optional numberOfInstances As Nullable(Of Integer) = null, Optional commonResourceFiles As IList(Of ResourceFile) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings : string * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings" Usage="new Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings (coordinationCommandLine, numberOfInstances, commonResourceFiles)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="coordinationCommandLine" Type="System.String" />
        <Parameter Name="numberOfInstances" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="commonResourceFiles" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt;" />
      </Parameters>
      <Docs>
        <param name="coordinationCommandLine"><span data-ttu-id="0a9d7-104">Die auszuführende Befehlszeile auf den Serverknoten zum Koordinieren der beim Aktivieren der primären führt den Befehl "Task" main ".</span><span class="sxs-lookup"><span data-stu-id="0a9d7-104">The command line to run on all the compute nodes to enable them to coordinate when the primary runs the main task command.</span></span></param>
        <param name="numberOfInstances"><span data-ttu-id="0a9d7-105">Die Anzahl der Computeknoten, die vom Task benötigt werden.</span><span class="sxs-lookup"><span data-stu-id="0a9d7-105">The number of compute nodes required by the task.</span></span></param>
        <param name="commonResourceFiles"><span data-ttu-id="0a9d7-106">Eine Liste der Dateien, die der Batch-Dienst vor dem Ausführen der Befehlszeile Koordinierung heruntergeladen wird.</span><span class="sxs-lookup"><span data-stu-id="0a9d7-106">A list of files that the Batch service will download before running the coordination command line.</span></span></param>
        <summary>
            <span data-ttu-id="0a9d7-107">Initialisiert eine neue Instanz der MultiInstanceSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0a9d7-107">Initializes a new instance of the MultiInstanceSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommonResourceFiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; CommonResourceFiles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; CommonResourceFiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings.CommonResourceFiles" />
      <MemberSignature Language="VB.NET" Value="Public Property CommonResourceFiles As IList(Of ResourceFile)" />
      <MemberSignature Language="F#" Value="member this.CommonResourceFiles : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings.CommonResourceFiles" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="commonResourceFiles")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0a9d7-108">Ruft ab oder Festlegen einer Liste von Dateien, die der Batch-Dienst vor dem Ausführen der Befehlszeile Koordinierung heruntergeladen wird.</span><span class="sxs-lookup"><span data-stu-id="0a9d7-108">Gets or sets a list of files that the Batch service will download before running the coordination command line.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="0a9d7-109">Der Unterschied zwischen allgemeinen Ressourcendateien und Ressourcendateien Aufgabe ist, dass allgemeine Ressourcendateien für alle Unteraufgaben an, einschließlich der primären heruntergeladen werden, während nur für die primäre Aufgabe Ressourcendateien heruntergeladen werden.</span><span class="sxs-lookup"><span data-stu-id="0a9d7-109">The difference between common resource files and task resource files is that common resource files are downloaded for all subtasks including the primary, whereas task resource files are downloaded only for the primary.</span></span> <span data-ttu-id="0a9d7-110">Beachten Sie außerdem, dass diese Ressourcendateien werden nicht auf das Arbeitsverzeichnis für den Task heruntergeladen, aber stattdessen auf das Stammverzeichnis des Vorgangs (ein Verzeichnis über das Arbeitsverzeichnis) heruntergeladen werden.</span><span class="sxs-lookup"><span data-stu-id="0a9d7-110">Also note that these resource files are not downloaded to the task working directory, but instead are downloaded to the task root directory (one directory above the working directory).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CoordinationCommandLine">
      <MemberSignature Language="C#" Value="public string CoordinationCommandLine { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CoordinationCommandLine" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings.CoordinationCommandLine" />
      <MemberSignature Language="VB.NET" Value="Public Property CoordinationCommandLine As String" />
      <MemberSignature Language="F#" Value="member this.CoordinationCommandLine : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings.CoordinationCommandLine" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="coordinationCommandLine")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0a9d7-111">Abrufen oder Festlegen der Befehlszeile auf den Serverknoten, zu ermöglichen, zum Koordinieren der Ausführung des primären den Befehl "Task" main "ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="0a9d7-111">Gets or sets the command line to run on all the compute nodes to enable them to coordinate when the primary runs the main task command.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="0a9d7-112">Typische Koordinierung über die Befehlszeile einen Hintergrunddienst startet und stellt sicher, dass der Dienst zum Verarbeiten von Nachrichten zwischen Knoten bereit ist.</span><span class="sxs-lookup"><span data-stu-id="0a9d7-112">A typical coordination command line launches a background service and verifies that the service is ready to process inter-node messages.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="NumberOfInstances">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; NumberOfInstances { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; NumberOfInstances" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings.NumberOfInstances" />
      <MemberSignature Language="VB.NET" Value="Public Property NumberOfInstances As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.NumberOfInstances : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings.NumberOfInstances" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="numberOfInstances")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0a9d7-113">Ruft ab oder legt die Anzahl von Serverknoten, die von der Aufgabe erforderlich sind.</span><span class="sxs-lookup"><span data-stu-id="0a9d7-113">Gets or sets the number of compute nodes required by the task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="0a9d7-114">Wenn nicht angegeben, ist der Standardwert 1.</span><span class="sxs-lookup"><span data-stu-id="0a9d7-114">If omitted, the default is 1.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="multiInstanceSettings.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0a9d7-115">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="0a9d7-115">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="0a9d7-116">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="0a9d7-116">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>