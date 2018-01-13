<Type Name="ComputeNodeError" FullName="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError">
  <TypeSignature Language="C#" Value="public class ComputeNodeError" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ComputeNodeError extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError" />
  <TypeSignature Language="VB.NET" Value="Public Class ComputeNodeError" />
  <TypeSignature Language="F#" Value="type ComputeNodeError = class" />
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
            Ein Fehler aufgetreten, die von einem Serverknoten.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComputeNodeError ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError.#ctor" />
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
            Initialisiert eine neue Instanz der ComputeNodeError-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComputeNodeError (string code = null, string message = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt; errorDetails = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string code, string message, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt; errorDetails) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError.#ctor(System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.NameValuePair})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional code As String = null, Optional message As String = null, Optional errorDetails As IList(Of NameValuePair) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError : string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError" Usage="new Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError (code, message, errorDetails)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="code" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="errorDetails" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt;" />
      </Parameters>
      <Docs>
        <param name="code">Ein Bezeichner für die Compute-Knoten-Fehler. Codes sind unveränderlich und programmgesteuert genutzt werden sollen.</param>
        <param name="message">Eine Nachricht, die Beschreibung des Fehlers Compute-Knoten bestimmt, eignet sich für die Anzeige in einer Benutzeroberfläche.</param>
        <param name="errorDetails">Die Liste der zusätzlichen Fehlerinformationen im Zusammenhang mit der Compute-Knoten-Fehler.</param>
        <summary>
            Initialisiert eine neue Instanz der ComputeNodeError-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public string Code { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError.Code" />
      <MemberSignature Language="VB.NET" Value="Public Property Code As String" />
      <MemberSignature Language="F#" Value="member this.Code : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError.Code" />
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
            Ruft ab oder legt einen Bezeichner für den Fehler der Compute-Knoten. Codes sind unveränderlich und programmgesteuert genutzt werden sollen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorDetails">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt; ErrorDetails { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt; ErrorDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError.ErrorDetails" />
      <MemberSignature Language="VB.NET" Value="Public Property ErrorDetails As IList(Of NameValuePair)" />
      <MemberSignature Language="F#" Value="member this.ErrorDetails : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError.ErrorDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="errorDetails")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NameValuePair&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der zusätzlichen Fehlerinformationen im Zusammenhang mit der Compute-Knoten-Fehler.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError.Message" />
      <MemberSignature Language="VB.NET" Value="Public Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError.Message" />
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
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder festlegen eine Meldung Compute Knoten, für die Anzeige in einer Benutzeroberfläche geeignet sein soll.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>