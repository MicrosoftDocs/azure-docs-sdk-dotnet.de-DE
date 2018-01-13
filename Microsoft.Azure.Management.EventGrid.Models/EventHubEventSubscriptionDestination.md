<Type Name="EventHubEventSubscriptionDestination" FullName="Microsoft.Azure.Management.EventGrid.Models.EventHubEventSubscriptionDestination">
  <TypeSignature Language="C#" Value="public class EventHubEventSubscriptionDestination : Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionDestination" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EventHubEventSubscriptionDestination extends Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionDestination" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.EventGrid.Models.EventHubEventSubscriptionDestination" />
  <TypeSignature Language="VB.NET" Value="Public Class EventHubEventSubscriptionDestination&#xA;Inherits EventSubscriptionDestination" />
  <TypeSignature Language="F#" Value="type EventHubEventSubscriptionDestination = class&#xA;    inherit EventSubscriptionDestination" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionDestination</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("EventHub")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Informationen zu den Event Hub-Ziel für Ereignisabonnement
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventHubEventSubscriptionDestination ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.Models.EventHubEventSubscriptionDestination.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der EventHubEventSubscriptionDestination-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventHubEventSubscriptionDestination (string resourceId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string resourceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.Models.EventHubEventSubscriptionDestination.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional resourceId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.EventGrid.Models.EventHubEventSubscriptionDestination : string -&gt; Microsoft.Azure.Management.EventGrid.Models.EventHubEventSubscriptionDestination" Usage="new Microsoft.Azure.Management.EventGrid.Models.EventHubEventSubscriptionDestination resourceId" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="resourceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resourceId">Die Azure-Ressourcen-Id, die den Endpunkt des ein Event Hub-Ziel von Ereignisabonnement darstellt.</param>
        <summary>
            Initialisiert eine neue Instanz der EventHubEventSubscriptionDestination-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceId">
      <MemberSignature Language="C#" Value="public string ResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.EventHubEventSubscriptionDestination.ResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceId As String" />
      <MemberSignature Language="F#" Value="member this.ResourceId : string with get, set" Usage="Microsoft.Azure.Management.EventGrid.Models.EventHubEventSubscriptionDestination.ResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.resourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Azure-Ressourcen-Id, die den Endpunkt des ein Event Hub-Ziel von Ereignisabonnement darstellt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>