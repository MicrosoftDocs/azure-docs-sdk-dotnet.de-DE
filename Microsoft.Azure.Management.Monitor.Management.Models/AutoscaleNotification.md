<Type Name="AutoscaleNotification" FullName="Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleNotification">
  <TypeSignature Language="C#" Value="public class AutoscaleNotification" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi AutoscaleNotification extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleNotification" />
  <TypeSignature Language="VB.NET" Value="Public Class AutoscaleNotification" />
  <TypeSignature Language="F#" Value="type AutoscaleNotification = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Benachrichtigung für automatische Skalierung.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoscaleNotification ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleNotification.#ctor" />
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
            Initialisiert eine neue Instanz der AutoscaleNotification-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoscaleNotification (Microsoft.Azure.Management.Monitor.Management.Models.EmailNotification email = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.WebhookNotification&gt; webhooks = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Monitor.Management.Models.EmailNotification email, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.WebhookNotification&gt; webhooks) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleNotification.#ctor(Microsoft.Azure.Management.Monitor.Management.Models.EmailNotification,System.Collections.Generic.IList{Microsoft.Azure.Management.Monitor.Management.Models.WebhookNotification})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional email As EmailNotification = null, Optional webhooks As IList(Of WebhookNotification) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleNotification : Microsoft.Azure.Management.Monitor.Management.Models.EmailNotification * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.WebhookNotification&gt; -&gt; Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleNotification" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleNotification (email, webhooks)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="email" Type="Microsoft.Azure.Management.Monitor.Management.Models.EmailNotification" />
        <Parameter Name="webhooks" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.WebhookNotification&gt;" />
      </Parameters>
      <Docs>
        <param name="email">die e-Mail-Benachrichtigung.</param>
        <param name="webhooks">die Auflistung von Webhook Benachrichtigungen.</param>
        <summary>
            Initialisiert eine neue Instanz der AutoscaleNotification-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Email">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.Models.EmailNotification Email { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Management.Models.EmailNotification Email" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleNotification.Email" />
      <MemberSignature Language="VB.NET" Value="Public Property Email As EmailNotification" />
      <MemberSignature Language="F#" Value="member this.Email : Microsoft.Azure.Management.Monitor.Management.Models.EmailNotification with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleNotification.Email" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="email")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.EmailNotification</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die e-Mail-Benachrichtigung.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Operation">
      <MemberSignature Language="C#" Value="public static string Operation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string Operation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleNotification.Operation" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property Operation As String" />
      <MemberSignature Language="F#" Value="member this.Operation : string" Usage="Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleNotification.Operation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="operation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            der Vorgang der Benachrichtigung zugeordnet, und sein Wert muss "Scale"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Webhooks">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.WebhookNotification&gt; Webhooks { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.WebhookNotification&gt; Webhooks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleNotification.Webhooks" />
      <MemberSignature Language="VB.NET" Value="Public Property Webhooks As IList(Of WebhookNotification)" />
      <MemberSignature Language="F#" Value="member this.Webhooks : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.WebhookNotification&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleNotification.Webhooks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="webhooks")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.WebhookNotification&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Auflistung der Webhook Benachrichtigungen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>