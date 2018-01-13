<Type Name="BatchError" FullName="Microsoft.Azure.Batch.Protocol.Models.BatchError">
  <TypeSignature Language="C#" Value="public class BatchError" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BatchError extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.BatchError" />
  <TypeSignature Language="VB.NET" Value="Public Class BatchError" />
  <TypeSignature Language="F#" Value="type BatchError = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Eine Fehlerantwort aus dem Azure Batch-Dienst empfangen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BatchError ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.BatchError.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der BatchError-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BatchError (string code = null, Microsoft.Azure.Batch.Protocol.Models.ErrorMessage message = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.BatchErrorDetail&gt; values = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string code, class Microsoft.Azure.Batch.Protocol.Models.ErrorMessage message, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.BatchErrorDetail&gt; values) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.BatchError.#ctor(System.String,Microsoft.Azure.Batch.Protocol.Models.ErrorMessage,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.BatchErrorDetail})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional code As String = null, Optional message As ErrorMessage = null, Optional values As IList(Of BatchErrorDetail) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.BatchError : string * Microsoft.Azure.Batch.Protocol.Models.ErrorMessage * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.BatchErrorDetail&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.BatchError" Usage="new Microsoft.Azure.Batch.Protocol.Models.BatchError (code, message, values)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="code" Type="System.String" />
        <Parameter Name="message" Type="Microsoft.Azure.Batch.Protocol.Models.ErrorMessage" />
        <Parameter Name="values" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.BatchErrorDetail&gt;" />
      </Parameters>
      <Docs>
        <param name="code">Ein Bezeichner für den Fehler. Codes sind unveränderlich und programmgesteuert genutzt werden sollen.</param>
        <param name="message">Eine Meldung, die Beschreibung des Fehlers, der für die Anzeige in einer Benutzeroberfläche geeignet sein soll.</param>
        <param name="values">Eine Auflistung von Schlüssel-Wert-Paaren, die zusätzliche Informationen über den Fehler enthält.</param>
        <summary>
            Initialisiert eine neue Instanz der BatchError-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public string Code { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.BatchError.Code" />
      <MemberSignature Language="VB.NET" Value="Public Property Code As String" />
      <MemberSignature Language="F#" Value="member this.Code : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.BatchError.Code" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="code")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Bezeichner für den Fehler. Codes sind unveränderlich und programmgesteuert genutzt werden sollen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.ErrorMessage Message { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.ErrorMessage Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.BatchError.Message" />
      <MemberSignature Language="VB.NET" Value="Public Property Message As ErrorMessage" />
      <MemberSignature Language="F#" Value="member this.Message : Microsoft.Azure.Batch.Protocol.Models.ErrorMessage with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.BatchError.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="message")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ErrorMessage</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder festlegen eine Nachricht, die Beschreibung des Fehlers, der für die Anzeige in einer Benutzeroberfläche geeignet sein soll.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Values">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.BatchErrorDetail&gt; Values { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.BatchErrorDetail&gt; Values" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.BatchError.Values" />
      <MemberSignature Language="VB.NET" Value="Public Property Values As IList(Of BatchErrorDetail)" />
      <MemberSignature Language="F#" Value="member this.Values : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.BatchErrorDetail&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.BatchError.Values" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="values")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.BatchErrorDetail&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Auflistung von Schlüssel-Wert-Paaren, die zusätzliche Informationen über den Fehler enthält.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>