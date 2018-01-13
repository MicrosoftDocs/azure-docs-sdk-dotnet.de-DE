<Type Name="TroubleshootingDetails" FullName="Microsoft.Azure.Management.Network.Models.TroubleshootingDetails">
  <TypeSignature Language="C#" Value="public class TroubleshootingDetails" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TroubleshootingDetails extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.TroubleshootingDetails" />
  <TypeSignature Language="VB.NET" Value="Public Class TroubleshootingDetails" />
  <TypeSignature Language="F#" Value="type TroubleshootingDetails = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Informationen, die aus der angegebenen Ressource Problembehandlung gewonnen werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TroubleshootingDetails ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.TroubleshootingDetails.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der TroubleshootingDetails-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TroubleshootingDetails (string id = null, string reasonType = null, string summary = null, string detail = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingRecommendedActions&gt; recommendedActions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string reasonType, string summary, string detail, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.TroubleshootingRecommendedActions&gt; recommendedActions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.TroubleshootingDetails.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.TroubleshootingRecommendedActions})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional reasonType As String = null, Optional summary As String = null, Optional detail As String = null, Optional recommendedActions As IList(Of TroubleshootingRecommendedActions) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.TroubleshootingDetails : string * string * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingRecommendedActions&gt; -&gt; Microsoft.Azure.Management.Network.Models.TroubleshootingDetails" Usage="new Microsoft.Azure.Management.Network.Models.TroubleshootingDetails (id, reasonType, summary, detail, recommendedActions)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="reasonType" Type="System.String" />
        <Parameter Name="summary" Type="System.String" />
        <Parameter Name="detail" Type="System.String" />
        <Parameter Name="recommendedActions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingRecommendedActions&gt;" />
      </Parameters>
      <Docs>
        <param name="id">Die Id der Get Problembehandlung bei Vorgang.</param>
        <param name="reasonType">Typ der Ursache des Fehlers.</param>
        <param name="summary">Eine Zusammenfassung der Problembehandlung.</param>
        <param name="detail">Informationen zur Behandlung von Ergebnissen.</param>
        <param name="recommendedActions">Liste der empfohlenen Aktionen.</param>
        <summary>
            Initialisiert eine neue Instanz der TroubleshootingDetails-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Detail">
      <MemberSignature Language="C#" Value="public string Detail { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Detail" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.TroubleshootingDetails.Detail" />
      <MemberSignature Language="VB.NET" Value="Public Property Detail As String" />
      <MemberSignature Language="F#" Value="member this.Detail : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.TroubleshootingDetails.Detail" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="detail")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Details zur Behandlung von Ergebnissen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.TroubleshootingDetails.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.TroubleshootingDetails.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Id der Get Problembehandlung bei Vorgang.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReasonType">
      <MemberSignature Language="C#" Value="public string ReasonType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReasonType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.TroubleshootingDetails.ReasonType" />
      <MemberSignature Language="VB.NET" Value="Public Property ReasonType As String" />
      <MemberSignature Language="F#" Value="member this.ReasonType : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.TroubleshootingDetails.ReasonType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="reasonType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest Grund Fehler.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecommendedActions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingRecommendedActions&gt; RecommendedActions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.TroubleshootingRecommendedActions&gt; RecommendedActions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.TroubleshootingDetails.RecommendedActions" />
      <MemberSignature Language="VB.NET" Value="Public Property RecommendedActions As IList(Of TroubleshootingRecommendedActions)" />
      <MemberSignature Language="F#" Value="member this.RecommendedActions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingRecommendedActions&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.TroubleshootingDetails.RecommendedActions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recommendedActions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingRecommendedActions&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der empfohlenen Aktionen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Summary">
      <MemberSignature Language="C#" Value="public string Summary { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Summary" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.TroubleshootingDetails.Summary" />
      <MemberSignature Language="VB.NET" Value="Public Property Summary As String" />
      <MemberSignature Language="F#" Value="member this.Summary : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.TroubleshootingDetails.Summary" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="summary")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert einen Überblick über die Problembehandlung.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>