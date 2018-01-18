<Type Name="ScheduleCreateOrUpdateParameters" FullName="Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateParameters">
  <TypeSignature Language="C#" Value="public class ScheduleCreateOrUpdateParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ScheduleCreateOrUpdateParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class ScheduleCreateOrUpdateParameters" />
  <TypeSignature Language="F#" Value="type ScheduleCreateOrUpdateParameters = class" />
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
            <span data-ttu-id="6263a-101">Die Parameter für den Zeitplan erstellen oder Aktualisieren zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="6263a-101">The parameters supplied to the create or update schedule operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScheduleCreateOrUpdateParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6263a-102">Initialisiert eine neue Instanz der ScheduleCreateOrUpdateParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6263a-102">Initializes a new instance of the ScheduleCreateOrUpdateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScheduleCreateOrUpdateParameters (string name, Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateProperties properties);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateProperties properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateParameters.#ctor(System.String,Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateProperties)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, properties As ScheduleCreateOrUpdateProperties)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateParameters : string * Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateProperties -&gt; Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateParameters" Usage="new Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateParameters (name, properties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="properties" Type="Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateProperties" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <param name="properties">To be added.</param>
        <summary>
            <span data-ttu-id="6263a-103">Initialisiert eine neue Instanz der ScheduleCreateOrUpdateParameters-Klasse mit erforderlichen Argumenten.</span><span class="sxs-lookup"><span data-stu-id="6263a-103">Initializes a new instance of the ScheduleCreateOrUpdateParameters class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConvertTimesFromTimeZone">
      <MemberSignature Language="C#" Value="public bool ConvertTimesFromTimeZone { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ConvertTimesFromTimeZone" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateParameters.ConvertTimesFromTimeZone" />
      <MemberSignature Language="VB.NET" Value="Public Property ConvertTimesFromTimeZone As Boolean" />
      <MemberSignature Language="F#" Value="member this.ConvertTimesFromTimeZone : bool with get, set" Usage="Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateParameters.ConvertTimesFromTimeZone" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6263a-104">Optional.</span><span class="sxs-lookup"><span data-stu-id="6263a-104">Optional.</span></span> <span data-ttu-id="6263a-105">"True", wenn momentaufnahmedauer wurden in der angegebenen Zeitzone angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="6263a-105">True if times provided are specified in the provided time zone.</span></span> <span data-ttu-id="6263a-106">False, wenn die Zeiten in UTC angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="6263a-106">False if times are in UTC.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateParameters.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateParameters.Name" />
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
            <span data-ttu-id="6263a-107">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="6263a-107">Required.</span></span> <span data-ttu-id="6263a-108">Ruft ab oder legt den Namen des Zeitplans.</span><span class="sxs-lookup"><span data-stu-id="6263a-108">Gets or sets the name of the schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateProperties Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateProperties Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateParameters.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As ScheduleCreateOrUpdateProperties" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateProperties with get, set" Usage="Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateParameters.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6263a-109">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="6263a-109">Required.</span></span> <span data-ttu-id="6263a-110">Ruft ab oder legt die Liste der Zeitplaneigenschaften.</span><span class="sxs-lookup"><span data-stu-id="6263a-110">Gets or sets the list of schedule properties.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>