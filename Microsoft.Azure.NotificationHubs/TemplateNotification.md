<Type Name="TemplateNotification" FullName="Microsoft.Azure.NotificationHubs.TemplateNotification">
  <TypeSignature Language="C#" Value="public sealed class TemplateNotification : Microsoft.Azure.NotificationHubs.Notification" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit TemplateNotification extends Microsoft.Azure.NotificationHubs.Notification" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.TemplateNotification" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TemplateNotification&#xA;Inherits Notification" />
  <TypeSignature Language="F#" Value="type TemplateNotification = class&#xA;    inherit Notification" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.NotificationHubs.Notification</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Stellt eine vorlagenbenachrichtigung dar.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TemplateNotification (System.Collections.Generic.IDictionary&lt;string,string&gt; templateProperties);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; templateProperties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TemplateNotification.#ctor(System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (templateProperties As IDictionary(Of String, String))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.TemplateNotification : System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.NotificationHubs.TemplateNotification" Usage="new Microsoft.Azure.NotificationHubs.TemplateNotification templateProperties" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="templateProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="templateProperties">Die Eigenschaften der Vorlage.</param>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.TemplateNotification" />-Klasse.</summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Eigenschaften</exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TemplateNotification (System.Collections.Generic.IDictionary&lt;string,string&gt; templateProperties, string tag);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; templateProperties, string tag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TemplateNotification.#ctor(System.Collections.Generic.IDictionary{System.String,System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (templateProperties As IDictionary(Of String, String), tag As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.TemplateNotification : System.Collections.Generic.IDictionary&lt;string, string&gt; * string -&gt; Microsoft.Azure.NotificationHubs.TemplateNotification" Usage="new Microsoft.Azure.NotificationHubs.TemplateNotification (templateProperties, tag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This method is obsolete.")</AttributeName>
        </Attribute>
      </Attributes>
      <Parameters>
        <Parameter Name="templateProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="tag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="templateProperties">Die Eigenschaften der Vorlage.</param>
        <param name="tag">Die Benachrichtigung-Tag.</param>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.TemplateNotification" />-Klasse.</summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Eigenschaften</exception>
      </Docs>
    </Member>
    <Member MemberName="OnValidateAndPopulateHeaders">
      <MemberSignature Language="C#" Value="protected override void OnValidateAndPopulateHeaders ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnValidateAndPopulateHeaders() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.TemplateNotification.OnValidateAndPopulateHeaders" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnValidateAndPopulateHeaders ()" />
      <MemberSignature Language="F#" Value="override this.OnValidateAndPopulateHeaders : unit -&gt; unit" Usage="templateNotification.OnValidateAndPopulateHeaders " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Überprüfen und füllt die Header.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PlatformType">
      <MemberSignature Language="C#" Value="protected override string PlatformType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PlatformType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.TemplateNotification.PlatformType" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property PlatformType As String" />
      <MemberSignature Language="F#" Value="member this.PlatformType : string" Usage="Microsoft.Azure.NotificationHubs.TemplateNotification.PlatformType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Typ der Plattform ab.
            </summary>
        <value>
            Der Typ der Plattform.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>