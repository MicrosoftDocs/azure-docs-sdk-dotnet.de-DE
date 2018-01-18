<Type Name="ExitCodeRangeMapping" FullName="Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping">
  <TypeSignature Language="C#" Value="public class ExitCodeRangeMapping" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExitCodeRangeMapping extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping" />
  <TypeSignature Language="VB.NET" Value="Public Class ExitCodeRangeMapping" />
  <TypeSignature Language="F#" Value="type ExitCodeRangeMapping = class" />
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
            <span data-ttu-id="bc7a5-101">Ein Bereich des Exitcodes und wie der Batch-Dienst reagieren soll, um Codes innerhalb dieses Bereichs zu beenden.</span><span class="sxs-lookup"><span data-stu-id="bc7a5-101">A range of exit codes and how the Batch service should respond to exit codes within that range.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExitCodeRangeMapping ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping.#ctor" />
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
            <span data-ttu-id="bc7a5-102">Initialisiert eine neue Instanz der ExitCodeRangeMapping-Klasse.</span><span class="sxs-lookup"><span data-stu-id="bc7a5-102">Initializes a new instance of the ExitCodeRangeMapping class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExitCodeRangeMapping (int start, int end, Microsoft.Azure.Batch.Protocol.Models.ExitOptions exitOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 start, int32 end, class Microsoft.Azure.Batch.Protocol.Models.ExitOptions exitOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping.#ctor(System.Int32,System.Int32,Microsoft.Azure.Batch.Protocol.Models.ExitOptions)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping : int * int * Microsoft.Azure.Batch.Protocol.Models.ExitOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping" Usage="new Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping (start, end, exitOptions)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="start" Type="System.Int32" />
        <Parameter Name="end" Type="System.Int32" />
        <Parameter Name="exitOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ExitOptions" />
      </Parameters>
      <Docs>
        <param name="start"><span data-ttu-id="bc7a5-103">Die erste Exitcode im Bereich.</span><span class="sxs-lookup"><span data-stu-id="bc7a5-103">The first exit code in the range.</span></span></param>
        <param name="end"><span data-ttu-id="bc7a5-104">Der letzte Exitcode im Bereich.</span><span class="sxs-lookup"><span data-stu-id="bc7a5-104">The last exit code in the range.</span></span></param>
        <param name="exitOptions"><span data-ttu-id="bc7a5-105">Wie der Batch-Dienst reagieren soll, wenn die Aufgabe mit dem Exitcode im Bereich beginnen, Ende (inklusiv) beendet wird.</span><span class="sxs-lookup"><span data-stu-id="bc7a5-105">How the Batch service should respond if the task exits with an exit code in the range start to end (inclusive).</span></span></param>
        <summary>
            <span data-ttu-id="bc7a5-106">Initialisiert eine neue Instanz der ExitCodeRangeMapping-Klasse.</span><span class="sxs-lookup"><span data-stu-id="bc7a5-106">Initializes a new instance of the ExitCodeRangeMapping class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="End">
      <MemberSignature Language="C#" Value="public int End { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 End" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping.End" />
      <MemberSignature Language="VB.NET" Value="Public Property End As Integer" />
      <MemberSignature Language="F#" Value="member this.End : int with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping.End" />
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
            <span data-ttu-id="bc7a5-107">Ruft ab oder legt das letzten Exitcode im Bereich.</span><span class="sxs-lookup"><span data-stu-id="bc7a5-107">Gets or sets the last exit code in the range.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExitOptions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.ExitOptions ExitOptions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.ExitOptions ExitOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping.ExitOptions" />
      <MemberSignature Language="VB.NET" Value="Public Property ExitOptions As ExitOptions" />
      <MemberSignature Language="F#" Value="member this.ExitOptions : Microsoft.Azure.Batch.Protocol.Models.ExitOptions with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping.ExitOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="exitOptions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ExitOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bc7a5-108">Ruft ab oder legt sie fest, wie der Batch-Dienst reagieren soll, wenn die Aufgabe mit dem Exitcode im Bereich beginnen, Ende (inklusiv) beendet wird.</span><span class="sxs-lookup"><span data-stu-id="bc7a5-108">Gets or sets how the Batch service should respond if the task exits with an exit code in the range start to end (inclusive).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Start">
      <MemberSignature Language="C#" Value="public int Start { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Start" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping.Start" />
      <MemberSignature Language="VB.NET" Value="Public Property Start As Integer" />
      <MemberSignature Language="F#" Value="member this.Start : int with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping.Start" />
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
            <span data-ttu-id="bc7a5-109">Ruft ab oder legt den ersten Exitcode im Bereich.</span><span class="sxs-lookup"><span data-stu-id="bc7a5-109">Gets or sets the first exit code in the range.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="exitCodeRangeMapping.Validate " />
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
            <span data-ttu-id="bc7a5-110">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="bc7a5-110">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bc7a5-111">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="bc7a5-111">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>