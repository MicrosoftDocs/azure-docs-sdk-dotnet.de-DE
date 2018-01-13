<Type Name="ExitConditions" FullName="Microsoft.Azure.Batch.ExitConditions">
  <TypeSignature Language="C#" Value="public class ExitConditions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExitConditions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.ExitConditions" />
  <TypeSignature Language="VB.NET" Value="Public Class ExitConditions" />
  <TypeSignature Language="F#" Value="type ExitConditions = class&#xA;    interface ITransportObjectProvider&lt;ExitConditions&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            Wie der Batch-Dienst reagieren soll, wenn eine Aufgabe abgeschlossen ist.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExitConditions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ExitConditions.#ctor" />
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
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.ExitConditions" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Default">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.ExitOptions Default { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.ExitOptions Default" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ExitConditions.Default" />
      <MemberSignature Language="VB.NET" Value="Public Property Default As ExitOptions" />
      <MemberSignature Language="F#" Value="member this.Default : Microsoft.Azure.Batch.ExitOptions with get, set" Usage="Microsoft.Azure.Batch.ExitConditions.Default" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.ExitOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt sie fest, wie der Batch-Dienst reagieren soll, wenn der Task, mit der eine beenden-Bedingung, die nicht durch eine der anderen Eigenschaften abgedeckt fehlschlägt.
            </summary>
        <value>To be added.</value>
        <remarks>
            Dieser Wert wird verwendet, wenn die Aufgabe beendet, mit jeder Exitcode, die nicht aufgeführt wird, der <see cref="P:Microsoft.Azure.Batch.ExitConditions.ExitCodes" /> oder <see cref="P:Microsoft.Azure.Batch.ExitConditions.ExitCodeRanges" /> Auflistung und ein vorab verarbeitetes Fehler Wenn der <see cref="P:Microsoft.Azure.Batch.ExitConditions.PreProcessingError" /> Eigenschaft ist nicht vorhanden, oder mit einer Datei Hochladen fehlschlagen, wenn die <see cref="P:Microsoft.Azure.Batch.ExitConditions.FileUploadError" /> Eigenschaft ist nicht vorhanden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExitCodeRanges">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ExitCodeRangeMapping&gt; ExitCodeRanges { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.ExitCodeRangeMapping&gt; ExitCodeRanges" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ExitConditions.ExitCodeRanges" />
      <MemberSignature Language="VB.NET" Value="Public Property ExitCodeRanges As IList(Of ExitCodeRangeMapping)" />
      <MemberSignature Language="F#" Value="member this.ExitCodeRanges : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ExitCodeRangeMapping&gt; with get, set" Usage="Microsoft.Azure.Batch.ExitConditions.ExitCodeRanges" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ExitCodeRangeMapping&gt;</ReturnType>
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
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ExitCodeMapping&gt; ExitCodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.ExitCodeMapping&gt; ExitCodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ExitConditions.ExitCodes" />
      <MemberSignature Language="VB.NET" Value="Public Property ExitCodes As IList(Of ExitCodeMapping)" />
      <MemberSignature Language="F#" Value="member this.ExitCodes : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ExitCodeMapping&gt; with get, set" Usage="Microsoft.Azure.Batch.ExitConditions.ExitCodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ExitCodeMapping&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Liste der Aufgabe Exitcodes und wie der Batch-Dienst auf diese reagieren soll.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FileUploadError">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.ExitOptions FileUploadError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.ExitOptions FileUploadError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ExitConditions.FileUploadError" />
      <MemberSignature Language="VB.NET" Value="Public Property FileUploadError As ExitOptions" />
      <MemberSignature Language="F#" Value="member this.FileUploadError : Microsoft.Azure.Batch.ExitOptions with get, set" Usage="Microsoft.Azure.Batch.ExitConditions.FileUploadError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.ExitOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt sie fest, wie der Batch-Dienst reagieren soll, wenn ein Datei hochladen-Fehler auftritt.
            </summary>
        <value>To be added.</value>
        <remarks>
            Wenn der Task mit dem Exitcode beendet, die über angegeben wurde <see cref="P:Microsoft.Azure.Batch.ExitConditions.ExitCodes" /> oder <see cref="P:Microsoft.Azure.Batch.ExitConditions.ExitCodeRanges" />, klicken Sie dann einen Datei hochladen-Fehler aufgetreten, und die Aktion, die gemäß des Exitcodes hat Vorrang vor.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PreProcessingError">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.ExitOptions PreProcessingError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.ExitOptions PreProcessingError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ExitConditions.PreProcessingError" />
      <MemberSignature Language="VB.NET" Value="Public Property PreProcessingError As ExitOptions" />
      <MemberSignature Language="F#" Value="member this.PreProcessingError : Microsoft.Azure.Batch.ExitOptions with get, set" Usage="Microsoft.Azure.Batch.ExitConditions.PreProcessingError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.ExitOptions</ReturnType>
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