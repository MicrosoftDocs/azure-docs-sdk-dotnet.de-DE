<Type Name="TroubleshootingRecommendedActions" FullName="Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingRecommendedActions">
  <TypeSignature Language="C#" Value="public class TroubleshootingRecommendedActions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TroubleshootingRecommendedActions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingRecommendedActions" />
  <TypeSignature Language="VB.NET" Value="Public Class TroubleshootingRecommendedActions" />
  <TypeSignature Language="F#" Value="type TroubleshootingRecommendedActions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Empfohlene Maßnahmen auf Grundlage des ermittelten Probleme.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TroubleshootingRecommendedActions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingRecommendedActions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der TroubleshootingRecommendedActions-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TroubleshootingRecommendedActions (string actionId = null, string actionText = null, string actionUri = null, string actionUriText = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string actionId, string actionText, string actionUri, string actionUriText) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingRecommendedActions.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional actionId As String = null, Optional actionText As String = null, Optional actionUri As String = null, Optional actionUriText As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingRecommendedActions : string * string * string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingRecommendedActions" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingRecommendedActions (actionId, actionText, actionUri, actionUriText)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="actionId" Type="System.String" />
        <Parameter Name="actionText" Type="System.String" />
        <Parameter Name="actionUri" Type="System.String" />
        <Parameter Name="actionUriText" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="actionId">Die ID der empfohlenen Aktion.</param>
        <param name="actionText">Beschreibung der empfohlenen Aktionen.</param>
        <param name="actionUri">Der Uri, verknüpfen, um eine Dokumentation für die empfohlenen Aktionen in zur Problembehandlung.</param>
        <param name="actionUriText">Die Informationen aus dem URI für die empfohlenen Aktionen in zur Problembehandlung.</param>
        <summary>
            Initialisiert eine neue Instanz der TroubleshootingRecommendedActions-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActionId">
      <MemberSignature Language="C#" Value="public string ActionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ActionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingRecommendedActions.ActionId" />
      <MemberSignature Language="VB.NET" Value="Public Property ActionId As String" />
      <MemberSignature Language="F#" Value="member this.ActionId : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingRecommendedActions.ActionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="actionId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt-ID, der die empfohlene Aktion.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActionText">
      <MemberSignature Language="C#" Value="public string ActionText { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ActionText" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingRecommendedActions.ActionText" />
      <MemberSignature Language="VB.NET" Value="Public Property ActionText As String" />
      <MemberSignature Language="F#" Value="member this.ActionText : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingRecommendedActions.ActionText" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="actionText")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Beschreibung der empfohlenen Aktionen in.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActionUri">
      <MemberSignature Language="C#" Value="public string ActionUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ActionUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingRecommendedActions.ActionUri" />
      <MemberSignature Language="VB.NET" Value="Public Property ActionUri As String" />
      <MemberSignature Language="F#" Value="member this.ActionUri : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingRecommendedActions.ActionUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="actionUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert den Uri verknüpfen, um eine Dokumentation für die empfohlenen Aktionen in zur Problembehandlung.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActionUriText">
      <MemberSignature Language="C#" Value="public string ActionUriText { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ActionUriText" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingRecommendedActions.ActionUriText" />
      <MemberSignature Language="VB.NET" Value="Public Property ActionUriText As String" />
      <MemberSignature Language="F#" Value="member this.ActionUriText : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingRecommendedActions.ActionUriText" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="actionUriText")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Informationen aus dem URI für die empfohlenen Aktionen in zur Problembehandlung.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>