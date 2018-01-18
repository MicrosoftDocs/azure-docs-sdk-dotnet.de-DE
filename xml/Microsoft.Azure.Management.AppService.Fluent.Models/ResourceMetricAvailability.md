<Type Name="ResourceMetricAvailability" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricAvailability">
  <TypeSignature Language="C#" Value="public class ResourceMetricAvailability" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceMetricAvailability extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricAvailability" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceMetricAvailability" />
  <TypeSignature Language="F#" Value="type ResourceMetricAvailability = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e2550-101">Verfügbarkeit von Metriken und Aufbewahrung.</span><span class="sxs-lookup"><span data-stu-id="e2550-101">Metrics availability and retention.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceMetricAvailability ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricAvailability.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e2550-102">Initialisiert eine neue Instanz der ResourceMetricAvailability-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e2550-102">Initializes a new instance of the ResourceMetricAvailability class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceMetricAvailability (string timeGrain = null, string retention = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string timeGrain, string retention) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricAvailability.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional timeGrain As String = null, Optional retention As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricAvailability : string * string -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricAvailability" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricAvailability (timeGrain, retention)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="timeGrain" Type="System.String" />
        <Parameter Name="retention" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="timeGrain"><span data-ttu-id="e2550-103">Zeitkorn.</span><span class="sxs-lookup"><span data-stu-id="e2550-103">Time grain .</span></span></param>
        <param name="retention"><span data-ttu-id="e2550-104">Beibehaltungsdauer für die aktuelle Zeit Auflösung.</span><span class="sxs-lookup"><span data-stu-id="e2550-104">Retention period for the current time grain.</span></span></param>
        <summary>
            <span data-ttu-id="e2550-105">Initialisiert eine neue Instanz der ResourceMetricAvailability-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e2550-105">Initializes a new instance of the ResourceMetricAvailability class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Retention">
      <MemberSignature Language="C#" Value="public string Retention { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Retention" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricAvailability.Retention" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Retention As String" />
      <MemberSignature Language="F#" Value="member this.Retention : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricAvailability.Retention" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="retention")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e2550-106">Ruft die Beibehaltungsdauer für das aktuelle zeitkorn ab.</span><span class="sxs-lookup"><span data-stu-id="e2550-106">Gets retention period for the current time grain.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeGrain">
      <MemberSignature Language="C#" Value="public string TimeGrain { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TimeGrain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricAvailability.TimeGrain" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TimeGrain As String" />
      <MemberSignature Language="F#" Value="member this.TimeGrain : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricAvailability.TimeGrain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timeGrain")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e2550-107">Ruft die zeitkorn ab.</span><span class="sxs-lookup"><span data-stu-id="e2550-107">Gets time grain .</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>