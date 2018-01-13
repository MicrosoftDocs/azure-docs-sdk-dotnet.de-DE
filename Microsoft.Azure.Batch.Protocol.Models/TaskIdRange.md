<Type Name="TaskIdRange" FullName="Microsoft.Azure.Batch.Protocol.Models.TaskIdRange">
  <TypeSignature Language="C#" Value="public class TaskIdRange" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskIdRange extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.TaskIdRange" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskIdRange" />
  <TypeSignature Language="F#" Value="type TaskIdRange = class" />
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
            <span data-ttu-id="f117f-101">Eine Reihe von Aufgaben-IDs, von denen eine Aufgabe abhängen kann.</span><span class="sxs-lookup"><span data-stu-id="f117f-101">A range of task IDs that a task can depend on.</span></span> <span data-ttu-id="f117f-102">Alle Aufgaben-IDs im Bereich müssen erfolgreich abgeschlossen, bevor der abhängige Task geplant werden kann.</span><span class="sxs-lookup"><span data-stu-id="f117f-102">All tasks with IDs in the range must complete successfully before the dependent task can be scheduled.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="f117f-103">Anfang und Ende des Bereichs sind inklusiv.</span><span class="sxs-lookup"><span data-stu-id="f117f-103">The start and end of the range are inclusive.</span></span> <span data-ttu-id="f117f-104">Beispielsweise verfügt ein Bereich Start-9 und 12, stellt er Aufgaben "9", "10'"11"und" 12".</span><span class="sxs-lookup"><span data-stu-id="f117f-104">For example, if a range has start 9 and end 12, then it represents tasks '9', '10', '11' and '12'.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskIdRange ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskIdRange.#ctor" />
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
            <span data-ttu-id="f117f-105">Initialisiert eine neue Instanz der TaskIdRange-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f117f-105">Initializes a new instance of the TaskIdRange class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskIdRange (int start, int end);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 start, int32 end) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskIdRange.#ctor(System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (start As Integer, end As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.TaskIdRange : int * int -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskIdRange" Usage="new Microsoft.Azure.Batch.Protocol.Models.TaskIdRange (start, end)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="start" Type="System.Int32" />
        <Parameter Name="end" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="start"><span data-ttu-id="f117f-106">Der erste Task-ID im Bereich.</span><span class="sxs-lookup"><span data-stu-id="f117f-106">The first task ID in the range.</span></span></param>
        <param name="end"><span data-ttu-id="f117f-107">Die letzte Task-ID im Bereich.</span><span class="sxs-lookup"><span data-stu-id="f117f-107">The last task ID in the range.</span></span></param>
        <summary>
            <span data-ttu-id="f117f-108">Initialisiert eine neue Instanz der TaskIdRange-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f117f-108">Initializes a new instance of the TaskIdRange class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="End">
      <MemberSignature Language="C#" Value="public int End { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 End" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskIdRange.End" />
      <MemberSignature Language="VB.NET" Value="Public Property End As Integer" />
      <MemberSignature Language="F#" Value="member this.End : int with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskIdRange.End" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="end")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f117f-109">Ruft ab oder legt den letzten Task-ID im Bereich.</span><span class="sxs-lookup"><span data-stu-id="f117f-109">Gets or sets the last task ID in the range.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Start">
      <MemberSignature Language="C#" Value="public int Start { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Start" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskIdRange.Start" />
      <MemberSignature Language="VB.NET" Value="Public Property Start As Integer" />
      <MemberSignature Language="F#" Value="member this.Start : int with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskIdRange.Start" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="start")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f117f-110">Ruft ab oder legt den ersten Task-ID im Bereich.</span><span class="sxs-lookup"><span data-stu-id="f117f-110">Gets or sets the first task ID in the range.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskIdRange.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="taskIdRange.Validate " />
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
            <span data-ttu-id="f117f-111">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="f117f-111">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f117f-112">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="f117f-112">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>