<Type Name="InstallationTemplate" FullName="Microsoft.Azure.NotificationHubs.InstallationTemplate">
  <TypeSignature Language="C#" Value="public class InstallationTemplate" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit InstallationTemplate extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.InstallationTemplate" />
  <TypeSignature Language="VB.NET" Value="Public Class InstallationTemplate" />
  <TypeSignature Language="F#" Value="type InstallationTemplate = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject(ItemRequired=Newtonsoft.Json.Required.Default, MemberSerialization=Newtonsoft.Json.MemberSerialization.OptOut)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Stellt-Vorlage, die mit einer Instanz von gehören möglicherweise <see cref="T:Microsoft.Azure.NotificationHubs.Installation" /> Klasse
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InstallationTemplate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.InstallationTemplate.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Body">
      <MemberSignature Language="C#" Value="public string Body { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Body" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.InstallationTemplate.Body" />
      <MemberSignature Language="VB.NET" Value="Public Property Body As String" />
      <MemberSignature Language="F#" Value="member this.Body : string with get, set" Usage="Microsoft.Azure.NotificationHubs.InstallationTemplate.Body" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="body")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Vorlage-Text für die benachrichtigungsnutzlast der Platzhalter, um mit tatsächlichen Daten ausgefüllt werden, während des Sendevorgangs enthalten kann
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Expiry">
      <MemberSignature Language="C#" Value="public string Expiry { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Expiry" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.InstallationTemplate.Expiry" />
      <MemberSignature Language="VB.NET" Value="Public Property Expiry As String" />
      <MemberSignature Language="F#" Value="member this.Expiry : string with get, set" Usage="Microsoft.Azure.NotificationHubs.InstallationTemplate.Expiry" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="expiry")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Ablauf gilt für das Ziel mit dem APNS-Benachrichtigungen
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Headers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Headers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Headers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.InstallationTemplate.Headers" />
      <MemberSignature Language="VB.NET" Value="Public Property Headers As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Headers : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.NotificationHubs.InstallationTemplate.Headers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="headers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder Auflistung von Headern für MPNS dienenden Benachrichtigungen
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.InstallationTemplate.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.NotificationHubs.InstallationTemplate.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="tags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Auflistung von Tags für bestimmte Vorlage. Ususaly nur einen Tagnamen Vorlage sollte hier sein.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>