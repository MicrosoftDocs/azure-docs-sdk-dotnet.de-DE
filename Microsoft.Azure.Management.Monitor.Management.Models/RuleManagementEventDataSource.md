<Type Name="RuleManagementEventDataSource" FullName="Microsoft.Azure.Management.Monitor.Management.Models.RuleManagementEventDataSource">
  <TypeSignature Language="C#" Value="public class RuleManagementEventDataSource : Microsoft.Azure.Management.Monitor.Management.Models.RuleDataSource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RuleManagementEventDataSource extends Microsoft.Azure.Management.Monitor.Management.Models.RuleDataSource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.RuleManagementEventDataSource" />
  <TypeSignature Language="VB.NET" Value="Public Class RuleManagementEventDataSource&#xA;Inherits RuleDataSource" />
  <TypeSignature Language="F#" Value="type RuleManagementEventDataSource = class&#xA;    inherit RuleDataSource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Monitor.Management.Models.RuleDataSource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Microsoft.Azure.Management.Insights.Models.RuleManagementEventDataSource")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Eine Regel Management ereignisdatenquelle. In diesem Fall ist die Unterscheidungseigenschaft Felder immer RuleManagementEventDataSource.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RuleManagementEventDataSource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.RuleManagementEventDataSource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der RuleManagementEventDataSource-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RuleManagementEventDataSource (string resourceUri = null, string eventName = null, string eventSource = null, string level = null, string operationName = null, string resourceGroupName = null, string resourceProviderName = null, string status = null, string subStatus = null, Microsoft.Azure.Management.Monitor.Management.Models.RuleManagementEventClaimsDataSource claims = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string resourceUri, string eventName, string eventSource, string level, string operationName, string resourceGroupName, string resourceProviderName, string status, string subStatus, class Microsoft.Azure.Management.Monitor.Management.Models.RuleManagementEventClaimsDataSource claims) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.RuleManagementEventDataSource.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Monitor.Management.Models.RuleManagementEventClaimsDataSource)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional resourceUri As String = null, Optional eventName As String = null, Optional eventSource As String = null, Optional level As String = null, Optional operationName As String = null, Optional resourceGroupName As String = null, Optional resourceProviderName As String = null, Optional status As String = null, Optional subStatus As String = null, Optional claims As RuleManagementEventClaimsDataSource = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.RuleManagementEventDataSource : string * string * string * string * string * string * string * string * string * Microsoft.Azure.Management.Monitor.Management.Models.RuleManagementEventClaimsDataSource -&gt; Microsoft.Azure.Management.Monitor.Management.Models.RuleManagementEventDataSource" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.RuleManagementEventDataSource (resourceUri, eventName, eventSource, level, operationName, resourceGroupName, resourceProviderName, status, subStatus, claims)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="resourceUri" Type="System.String" />
        <Parameter Name="eventName" Type="System.String" />
        <Parameter Name="eventSource" Type="System.String" />
        <Parameter Name="level" Type="System.String" />
        <Parameter Name="operationName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderName" Type="System.String" />
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="subStatus" Type="System.String" />
        <Parameter Name="claims" Type="Microsoft.Azure.Management.Monitor.Management.Models.RuleManagementEventClaimsDataSource" />
      </Parameters>
      <Docs>
        <param name="resourceUri">Der Ressourcenbezeichner der Ressource die Regel überwacht. **Hinweis**: Diese Eigenschaft kann nicht aktualisiert werden, für eine vorhandene Regel.</param>
        <param name="eventName">der Name des Ereignisses.</param>
        <param name="eventSource">Die Ereignisquelle.</param>
        <param name="level">die Ebene.</param>
        <param name="operationName">Der Name des Vorgangs, die überprüft werden soll. Wenn kein Name angegeben ist, wird jeder Vorgang verglichen.</param>
        <param name="resourceGroupName">Der Name der Ressourcengruppe.</param>
        <param name="resourceProviderName">der Name des Ressourcenanbieters.</param>
        <param name="status">Der Status des Vorgangs, die überprüft werden soll. Wenn kein Status angegeben ist, wird jeder Status verglichen.</param>
        <param name="subStatus">der Unterstatus.</param>
        <param name="claims">die Ansprüche.</param>
        <summary>
            Initialisiert eine neue Instanz der RuleManagementEventDataSource-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Claims">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.Models.RuleManagementEventClaimsDataSource Claims { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Management.Models.RuleManagementEventClaimsDataSource Claims" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.RuleManagementEventDataSource.Claims" />
      <MemberSignature Language="VB.NET" Value="Public Property Claims As RuleManagementEventClaimsDataSource" />
      <MemberSignature Language="F#" Value="member this.Claims : Microsoft.Azure.Management.Monitor.Management.Models.RuleManagementEventClaimsDataSource with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.RuleManagementEventDataSource.Claims" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="claims")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.RuleManagementEventClaimsDataSource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Ansprüche.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventName">
      <MemberSignature Language="C#" Value="public string EventName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EventName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.RuleManagementEventDataSource.EventName" />
      <MemberSignature Language="VB.NET" Value="Public Property EventName As String" />
      <MemberSignature Language="F#" Value="member this.EventName : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.RuleManagementEventDataSource.EventName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="eventName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen des Ereignisses.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventSource">
      <MemberSignature Language="C#" Value="public string EventSource { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EventSource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.RuleManagementEventDataSource.EventSource" />
      <MemberSignature Language="VB.NET" Value="Public Property EventSource As String" />
      <MemberSignature Language="F#" Value="member this.EventSource : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.RuleManagementEventDataSource.EventSource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="eventSource")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Ereignisquelle.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Level">
      <MemberSignature Language="C#" Value="public string Level { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Level" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.RuleManagementEventDataSource.Level" />
      <MemberSignature Language="VB.NET" Value="Public Property Level As String" />
      <MemberSignature Language="F#" Value="member this.Level : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.RuleManagementEventDataSource.Level" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="level")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt sie fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationName">
      <MemberSignature Language="C#" Value="public string OperationName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OperationName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.RuleManagementEventDataSource.OperationName" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationName As String" />
      <MemberSignature Language="F#" Value="member this.OperationName : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.RuleManagementEventDataSource.OperationName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="operationName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen des Vorgangs, die überprüft werden soll.
            Wenn kein Name angegeben ist, wird jeder Vorgang verglichen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGroupName">
      <MemberSignature Language="C#" Value="public string ResourceGroupName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceGroupName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.RuleManagementEventDataSource.ResourceGroupName" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceGroupName As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGroupName : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.RuleManagementEventDataSource.ResourceGroupName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceGroupName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt der Name der Ressourcengruppe.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceProviderName">
      <MemberSignature Language="C#" Value="public string ResourceProviderName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceProviderName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.RuleManagementEventDataSource.ResourceProviderName" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceProviderName As String" />
      <MemberSignature Language="F#" Value="member this.ResourceProviderName : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.RuleManagementEventDataSource.ResourceProviderName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceProviderName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt der Name des Ressourcenanbieters.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public string Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.RuleManagementEventDataSource.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As String" />
      <MemberSignature Language="F#" Value="member this.Status : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.RuleManagementEventDataSource.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Status des Vorgangs, die überprüft werden soll. Wenn kein Status angegeben ist, wird jeder Status verglichen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubStatus">
      <MemberSignature Language="C#" Value="public string SubStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.RuleManagementEventDataSource.SubStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property SubStatus As String" />
      <MemberSignature Language="F#" Value="member this.SubStatus : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.RuleManagementEventDataSource.SubStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="subStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Unterstatus.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>