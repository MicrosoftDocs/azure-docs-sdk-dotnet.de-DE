<Type Name="JobScheduleCreateProperties" FullName="Microsoft.Azure.Management.Automation.Models.JobScheduleCreateProperties">
  <TypeSignature Language="C#" Value="public class JobScheduleCreateProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobScheduleCreateProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.Models.JobScheduleCreateProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class JobScheduleCreateProperties" />
  <TypeSignature Language="F#" Value="type JobScheduleCreateProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="64e26-101">Die Parameter, die auf den Auftrag-Zeitplan Erstellungsvorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="64e26-101">The parameters supplied to the create job schedule operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobScheduleCreateProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.Models.JobScheduleCreateProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="64e26-102">Initialisiert eine neue Instanz der JobScheduleCreateProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="64e26-102">Initializes a new instance of the JobScheduleCreateProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobScheduleCreateProperties (Microsoft.Azure.Management.Automation.Models.ScheduleAssociationProperty schedule, Microsoft.Azure.Management.Automation.Models.RunbookAssociationProperty runbook);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Automation.Models.ScheduleAssociationProperty schedule, class Microsoft.Azure.Management.Automation.Models.RunbookAssociationProperty runbook) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.Models.JobScheduleCreateProperties.#ctor(Microsoft.Azure.Management.Automation.Models.ScheduleAssociationProperty,Microsoft.Azure.Management.Automation.Models.RunbookAssociationProperty)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (schedule As ScheduleAssociationProperty, runbook As RunbookAssociationProperty)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Automation.Models.JobScheduleCreateProperties : Microsoft.Azure.Management.Automation.Models.ScheduleAssociationProperty * Microsoft.Azure.Management.Automation.Models.RunbookAssociationProperty -&gt; Microsoft.Azure.Management.Automation.Models.JobScheduleCreateProperties" Usage="new Microsoft.Azure.Management.Automation.Models.JobScheduleCreateProperties (schedule, runbook)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="schedule" Type="Microsoft.Azure.Management.Automation.Models.ScheduleAssociationProperty" />
        <Parameter Name="runbook" Type="Microsoft.Azure.Management.Automation.Models.RunbookAssociationProperty" />
      </Parameters>
      <Docs>
        <param name="schedule">To be added.</param>
        <param name="runbook">To be added.</param>
        <summary>
            <span data-ttu-id="64e26-103">Initialisiert eine neue Instanz der JobScheduleCreateProperties-Klasse mit erforderlichen Argumenten.</span><span class="sxs-lookup"><span data-stu-id="64e26-103">Initializes a new instance of the JobScheduleCreateProperties class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Parameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.JobScheduleCreateProperties.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public Property Parameters As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Parameters : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Automation.Models.JobScheduleCreateProperties.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="64e26-104">Optional.</span><span class="sxs-lookup"><span data-stu-id="64e26-104">Optional.</span></span> <span data-ttu-id="64e26-105">Ruft ab oder legt eine Liste der Auftragseigenschaften.</span><span class="sxs-lookup"><span data-stu-id="64e26-105">Gets or sets a list of job properties.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Runbook">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Automation.Models.RunbookAssociationProperty Runbook { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.Models.RunbookAssociationProperty Runbook" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.JobScheduleCreateProperties.Runbook" />
      <MemberSignature Language="VB.NET" Value="Public Property Runbook As RunbookAssociationProperty" />
      <MemberSignature Language="F#" Value="member this.Runbook : Microsoft.Azure.Management.Automation.Models.RunbookAssociationProperty with get, set" Usage="Microsoft.Azure.Management.Automation.Models.JobScheduleCreateProperties.Runbook" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.RunbookAssociationProperty</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="64e26-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="64e26-106">Required.</span></span> <span data-ttu-id="64e26-107">Ruft ab oder legt das Runbook.</span><span class="sxs-lookup"><span data-stu-id="64e26-107">Gets or sets the runbook.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunOn">
      <MemberSignature Language="C#" Value="public string RunOn { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RunOn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.JobScheduleCreateProperties.RunOn" />
      <MemberSignature Language="VB.NET" Value="Public Property RunOn As String" />
      <MemberSignature Language="F#" Value="member this.RunOn : string with get, set" Usage="Microsoft.Azure.Management.Automation.Models.JobScheduleCreateProperties.RunOn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="64e26-108">Optional.</span><span class="sxs-lookup"><span data-stu-id="64e26-108">Optional.</span></span> <span data-ttu-id="64e26-109">Ruft ab oder legt die Hybrid Worker-Gruppe, die der geplante Auftrag ausgeführt werden soll.</span><span class="sxs-lookup"><span data-stu-id="64e26-109">Gets or sets the hybrid worker group that the scheduled job should run on.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Schedule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Automation.Models.ScheduleAssociationProperty Schedule { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.Models.ScheduleAssociationProperty Schedule" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.JobScheduleCreateProperties.Schedule" />
      <MemberSignature Language="VB.NET" Value="Public Property Schedule As ScheduleAssociationProperty" />
      <MemberSignature Language="F#" Value="member this.Schedule : Microsoft.Azure.Management.Automation.Models.ScheduleAssociationProperty with get, set" Usage="Microsoft.Azure.Management.Automation.Models.JobScheduleCreateProperties.Schedule" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.ScheduleAssociationProperty</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="64e26-110">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="64e26-110">Required.</span></span> <span data-ttu-id="64e26-111">Ruft ab oder legt den Zeitplan fest.</span><span class="sxs-lookup"><span data-stu-id="64e26-111">Gets or sets the schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>