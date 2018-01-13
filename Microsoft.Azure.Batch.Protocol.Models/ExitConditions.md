<Type Name="ExitConditions" FullName="Microsoft.Azure.Batch.Protocol.Models.ExitConditions">
  <TypeSignature Language="C#" Value="public class ExitConditions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExitConditions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.ExitConditions" />
  <TypeSignature Language="VB.NET" Value="Public Class ExitConditions" />
  <TypeSignature Language="F#" Value="type ExitConditions = class" />
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
            Gibt an, wie der Batch-Dienst reagieren soll, wenn die Aufgabe abgeschlossen ist.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExitConditions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ExitConditions.#ctor" />
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
            Initialisiert eine neue Instanz der ExitConditions-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExitConditions (System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping&gt; exitCodes = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping&gt; exitCodeRanges = null, Microsoft.Azure.Batch.Protocol.Models.ExitOptions preProcessingError = null, Microsoft.Azure.Batch.Protocol.Models.ExitOptions fileUploadError = null, Microsoft.Azure.Batch.Protocol.Models.ExitOptions defaultProperty = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping&gt; exitCodes, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping&gt; exitCodeRanges, class Microsoft.Azure.Batch.Protocol.Models.ExitOptions preProcessingError, class Microsoft.Azure.Batch.Protocol.Models.ExitOptions fileUploadError, class Microsoft.Azure.Batch.Protocol.Models.ExitOptions defaultProperty) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ExitConditions.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping},Microsoft.Azure.Batch.Protocol.Models.ExitOptions,Microsoft.Azure.Batch.Protocol.Models.ExitOptions,Microsoft.Azure.Batch.Protocol.Models.ExitOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional exitCodes As IList(Of ExitCodeMapping) = null, Optional exitCodeRanges As IList(Of ExitCodeRangeMapping) = null, Optional preProcessingError As ExitOptions = null, Optional fileUploadError As ExitOptions = null, Optional defaultProperty As ExitOptions = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.ExitConditions : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping&gt; * Microsoft.Azure.Batch.Protocol.Models.ExitOptions * Microsoft.Azure.Batch.Protocol.Models.ExitOptions * Microsoft.Azure.Batch.Protocol.Models.ExitOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.ExitConditions" Usage="new Microsoft.Azure.Batch.Protocol.Models.ExitConditions (exitCodes, exitCodeRanges, preProcessingError, fileUploadError, defaultProperty)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="exitCodes" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping&gt;" />
        <Parameter Name="exitCodeRanges" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping&gt;" />
        <Parameter Name="preProcessingError" Type="Microsoft.Azure.Batch.Protocol.Models.ExitOptions" />
        <Parameter Name="fileUploadError" Type="Microsoft.Azure.Batch.Protocol.Models.ExitOptions" />
        <Parameter Name="defaultProperty" Type="Microsoft.Azure.Batch.Protocol.Models.ExitOptions" />
      </Parameters>
      <Docs>
        <param name="exitCodes">Eine Liste der einzelnen Vorgang Exitcodes und wie der Batch-Dienst auf diese reagieren soll.</param>
        <param name="exitCodeRanges">Eine Liste der Aufgabe beenden Code Bereiche und wie der Batch-Dienst auf diese reagieren soll.</param>
        <param name="preProcessingError">Wie der Batch-Dienst reagieren soll, wenn der Task fehlschlägt, wurde aufgrund eines Fehlers nicht gestartet.</param>
        <param name="fileUploadError">Wie der Batch-Dienst reagieren soll, wenn ein Datei hochladen-Fehler auftritt.</param>
        <param name="defaultProperty">Wie der Batch-Dienst reagieren soll, wenn der Task, mit der eine beenden-Bedingung, die nicht durch eine der anderen Eigenschaften abgedeckt fehlschlägt.</param>
        <summary>
            Initialisiert eine neue Instanz der ExitConditions-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultProperty">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.ExitOptions DefaultProperty { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.ExitOptions DefaultProperty" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ExitConditions.DefaultProperty" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultProperty As ExitOptions" />
      <MemberSignature Language="F#" Value="member this.DefaultProperty : Microsoft.Azure.Batch.Protocol.Models.ExitOptions with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ExitConditions.DefaultProperty" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="default")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ExitOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt sie fest, wie der Batch-Dienst reagieren soll, wenn der Task, mit der eine beenden-Bedingung, die nicht durch eine der anderen Eigenschaften abgedeckt fehlschlägt.
            </summary>
        <value>To be added.</value>
        <remarks>
            Dieser Wert wird verwendet, wenn die Aufgabe beendet alle Exitcode, die nicht in der Auflistung ExitCodes oder ExitCodeRanges aufgeführt, mit Fehler vor der Verarbeitung, wenn die PreProcessingError-Eigenschaft nicht vorhanden ist oder mit einem Fehler beim Dateiupload wird, wenn die FileUploadError-Eigenschaft nicht vorhanden ist. Wenn Sie nicht standardmäßige Verhalten in den Exitcode 0 möchten, müssen Sie explizit mithilfe der Auflistung ExitCodes oder ExitCodeRanges auflisten.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExitCodeRanges">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping&gt; ExitCodeRanges { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping&gt; ExitCodeRanges" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ExitConditions.ExitCodeRanges" />
      <MemberSignature Language="VB.NET" Value="Public Property ExitCodeRanges As IList(Of ExitCodeRangeMapping)" />
      <MemberSignature Language="F#" Value="member this.ExitCodeRanges : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ExitConditions.ExitCodeRanges" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="exitCodeRanges")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ExitCodeRangeMapping&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Liste der Aufgabe beenden Code Bereiche und wie der Batch-Dienst auf diese reagieren soll.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExitCodes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping&gt; ExitCodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping&gt; ExitCodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ExitConditions.ExitCodes" />
      <MemberSignature Language="VB.NET" Value="Public Property ExitCodes As IList(Of ExitCodeMapping)" />
      <MemberSignature Language="F#" Value="member this.ExitCodes : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ExitConditions.ExitCodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="exitCodes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ExitCodeMapping&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Liste der einzelnen Vorgang Exitcodes und wie der Batch-Dienst auf diese reagieren soll.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FileUploadError">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.ExitOptions FileUploadError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.ExitOptions FileUploadError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ExitConditions.FileUploadError" />
      <MemberSignature Language="VB.NET" Value="Public Property FileUploadError As ExitOptions" />
      <MemberSignature Language="F#" Value="member this.FileUploadError : Microsoft.Azure.Batch.Protocol.Models.ExitOptions with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ExitConditions.FileUploadError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="fileUploadError")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ExitOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt sie fest, wie der Batch-Dienst reagieren soll, wenn ein Datei hochladen-Fehler auftritt.
            </summary>
        <value>To be added.</value>
        <remarks>
            Wenn der Task mit dem Exitcode, die über ExitCodes oder ExitCodeRanges angegeben wurde beendet, und klicken Sie dann einen Datei hochladen-Fehler aufgetreten, hat die Aktion, die gemäß des Exitcodes Vorrang vor.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PreProcessingError">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.ExitOptions PreProcessingError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.ExitOptions PreProcessingError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ExitConditions.PreProcessingError" />
      <MemberSignature Language="VB.NET" Value="Public Property PreProcessingError As ExitOptions" />
      <MemberSignature Language="F#" Value="member this.PreProcessingError : Microsoft.Azure.Batch.Protocol.Models.ExitOptions with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ExitConditions.PreProcessingError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="preProcessingError")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ExitOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt sie fest, wie der Batch-Dienst reagieren soll, wenn der Task fehlschlägt, wurde aufgrund eines Fehlers nicht gestartet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>