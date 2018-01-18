<Type Name="JobDisableParameter" FullName="Microsoft.Azure.Batch.Protocol.Models.JobDisableParameter">
  <TypeSignature Language="C#" Value="public class JobDisableParameter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobDisableParameter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.JobDisableParameter" />
  <TypeSignature Language="VB.NET" Value="Public Class JobDisableParameter" />
  <TypeSignature Language="F#" Value="type JobDisableParameter = class" />
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
            <span data-ttu-id="bf617-101">Optionen, die bei der Deaktivierung eines Auftrags.</span><span class="sxs-lookup"><span data-stu-id="bf617-101">Options when disabling a job.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobDisableParameter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobDisableParameter.#ctor" />
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
            <span data-ttu-id="bf617-102">Initialisiert eine neue Instanz der JobDisableParameter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="bf617-102">Initializes a new instance of the JobDisableParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobDisableParameter (Microsoft.Azure.Batch.Protocol.Models.DisableJobOption disableTasks);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Batch.Protocol.Models.DisableJobOption disableTasks) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobDisableParameter.#ctor(Microsoft.Azure.Batch.Protocol.Models.DisableJobOption)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (disableTasks As DisableJobOption)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.JobDisableParameter : Microsoft.Azure.Batch.Protocol.Models.DisableJobOption -&gt; Microsoft.Azure.Batch.Protocol.Models.JobDisableParameter" Usage="new Microsoft.Azure.Batch.Protocol.Models.JobDisableParameter disableTasks" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="disableTasks" Type="Microsoft.Azure.Batch.Protocol.Models.DisableJobOption" />
      </Parameters>
      <Docs>
        <param name="disableTasks"><span data-ttu-id="bf617-103">Vorgehensweise mit aktiven Aufgaben, die dem Auftrag zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="bf617-103">What to do with active tasks associated with the job.</span></span></param>
        <summary>
            <span data-ttu-id="bf617-104">Initialisiert eine neue Instanz der JobDisableParameter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="bf617-104">Initializes a new instance of the JobDisableParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableTasks">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.DisableJobOption DisableTasks { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Batch.Protocol.Models.DisableJobOption DisableTasks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobDisableParameter.DisableTasks" />
      <MemberSignature Language="VB.NET" Value="Public Property DisableTasks As DisableJobOption" />
      <MemberSignature Language="F#" Value="member this.DisableTasks : Microsoft.Azure.Batch.Protocol.Models.DisableJobOption with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobDisableParameter.DisableTasks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="disableTasks")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.DisableJobOption</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf617-105">Ruft ab, oder legt ihn fest Vorgehensweise mit aktiven Aufgaben, die dem Auftrag zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="bf617-105">Gets or sets what to do with active tasks associated with the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="bf617-106">Folgende Werte sind möglich: "wieder in Warteschlange", "Beenden", "Warten"</span><span class="sxs-lookup"><span data-stu-id="bf617-106">Possible values include: 'requeue', 'terminate', 'wait'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobDisableParameter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="jobDisableParameter.Validate " />
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
            <span data-ttu-id="bf617-107">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="bf617-107">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf617-108">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="bf617-108">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>