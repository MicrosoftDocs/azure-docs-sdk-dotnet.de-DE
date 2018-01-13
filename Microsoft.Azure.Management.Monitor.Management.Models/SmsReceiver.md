<Type Name="SmsReceiver" FullName="Microsoft.Azure.Management.Monitor.Management.Models.SmsReceiver">
  <TypeSignature Language="C#" Value="public class SmsReceiver" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SmsReceiver extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.SmsReceiver" />
  <TypeSignature Language="VB.NET" Value="Public Class SmsReceiver" />
  <TypeSignature Language="F#" Value="type SmsReceiver = class" />
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
            Ein SMS-Empfänger.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SmsReceiver ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.SmsReceiver.#ctor" />
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
            Initialisiert eine neue Instanz der SmsReceiver-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SmsReceiver (string name, string countryCode, string phoneNumber, Nullable&lt;Microsoft.Azure.Management.Monitor.Management.Models.ReceiverStatus&gt; status = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string countryCode, string phoneNumber, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Monitor.Management.Models.ReceiverStatus&gt; status) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.SmsReceiver.#ctor(System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.Monitor.Management.Models.ReceiverStatus})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, countryCode As String, phoneNumber As String, Optional status As Nullable(Of ReceiverStatus) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.SmsReceiver : string * string * string * Nullable&lt;Microsoft.Azure.Management.Monitor.Management.Models.ReceiverStatus&gt; -&gt; Microsoft.Azure.Management.Monitor.Management.Models.SmsReceiver" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.SmsReceiver (name, countryCode, phoneNumber, status)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="countryCode" Type="System.String" />
        <Parameter Name="phoneNumber" Type="System.String" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.Monitor.Management.Models.ReceiverStatus&gt;" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des Empfängers SMS. Namen müssen über alle Empfänger innerhalb einer Aktivitätsgruppe eindeutig sein.</param>
        <param name="countryCode">Die Landeskennzahl des Empfängers SMS.</param>
        <param name="phoneNumber">Die Telefonnummer des Empfängers SMS.</param>
        <param name="status">Der Status des Empfängers. Folgende Werte sind möglich: "NotSpecified", "Aktiviert", "Deaktiviert"</param>
        <summary>
            Initialisiert eine neue Instanz der SmsReceiver-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CountryCode">
      <MemberSignature Language="C#" Value="public string CountryCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CountryCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.SmsReceiver.CountryCode" />
      <MemberSignature Language="VB.NET" Value="Public Property CountryCode As String" />
      <MemberSignature Language="F#" Value="member this.CountryCode : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.SmsReceiver.CountryCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="countryCode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Landeskennzahl des Empfängers SMS.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.SmsReceiver.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.SmsReceiver.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen des Empfängers SMS. Namen müssen über alle Empfänger innerhalb einer Aktivitätsgruppe eindeutig sein.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PhoneNumber">
      <MemberSignature Language="C#" Value="public string PhoneNumber { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PhoneNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.SmsReceiver.PhoneNumber" />
      <MemberSignature Language="VB.NET" Value="Public Property PhoneNumber As String" />
      <MemberSignature Language="F#" Value="member this.PhoneNumber : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.SmsReceiver.PhoneNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="phoneNumber")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Telefonnummer des Empfängers SMS.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Monitor.Management.Models.ReceiverStatus&gt; Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Monitor.Management.Models.ReceiverStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.SmsReceiver.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As Nullable(Of ReceiverStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.Monitor.Management.Models.ReceiverStatus&gt;" Usage="Microsoft.Azure.Management.Monitor.Management.Models.SmsReceiver.Status" />
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
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Monitor.Management.Models.ReceiverStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Status des Empfängers ab. Folgende Werte sind möglich: "NotSpecified", "Aktiviert", "Deaktiviert"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.SmsReceiver.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="smsReceiver.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>