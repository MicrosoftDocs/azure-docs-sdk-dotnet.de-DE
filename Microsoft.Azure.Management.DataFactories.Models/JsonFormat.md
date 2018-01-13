<Type Name="JsonFormat" FullName="Microsoft.Azure.Management.DataFactories.Models.JsonFormat">
  <TypeSignature Language="C#" Value="public class JsonFormat : Microsoft.Azure.Management.DataFactories.Models.StorageFormat" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JsonFormat extends Microsoft.Azure.Management.DataFactories.Models.StorageFormat" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.JsonFormat" />
  <TypeSignature Language="VB.NET" Value="Public Class JsonFormat&#xA;Inherits StorageFormat" />
  <TypeSignature Language="F#" Value="type JsonFormat = class&#xA;    inherit StorageFormat" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactories.Models.StorageFormat</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Die Daten im JSON-Format gespeichert.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JsonFormat ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.JsonFormat.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncodingName">
      <MemberSignature Language="C#" Value="public string EncodingName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EncodingName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.JsonFormat.EncodingName" />
      <MemberSignature Language="VB.NET" Value="Public Property EncodingName As String" />
      <MemberSignature Language="F#" Value="member this.EncodingName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.JsonFormat.EncodingName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Codepagename der bevorzugten Codierung. Wenn nicht angegeben ist, ist der Standardwert "Utf-8", es sei denn, einer anderen Codierung von Unicode-Byte-reihenfolgemarkierung (BOM) bezeichnet. Die vollständige Liste der unterstützten Werte finden Sie in der Spalte "Name" der Tabelle der Codierungen in den folgenden Verweis: https://msdn.microsoft.com/library/system.text.encoding.aspx#Anchor_5.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FilePattern">
      <MemberSignature Language="C#" Value="public string FilePattern { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FilePattern" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.JsonFormat.FilePattern" />
      <MemberSignature Language="VB.NET" Value="Public Property FilePattern As String" />
      <MemberSignature Language="F#" Value="member this.FilePattern : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.JsonFormat.FilePattern" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der JSON Dateimuster. Genauer gesagt die Methode zum Trennen von einzelnen JSON-Objekts sein. Muss einer der <see cref="T:Microsoft.Azure.Management.DataFactories.Models.JsonFormatFilePattern" />.
            Standardwert ist "SetOfObjects".
            Es wird die Groß-/Kleinschreibung beachtet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JsonNodeReference">
      <MemberSignature Language="C#" Value="public string JsonNodeReference { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string JsonNodeReference" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.JsonFormat.JsonNodeReference" />
      <MemberSignature Language="VB.NET" Value="Public Property JsonNodeReference As String" />
      <MemberSignature Language="F#" Value="member this.JsonNodeReference : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.JsonFormat.JsonNodeReference" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Optional. Die JSONPath des JSON-Array-Knotens, vereinfacht werden. Referenz: http://goessner.net/articles/JsonPath/.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JsonPathDefinition">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.Dictionary&lt;string,string&gt; JsonPathDefinition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.Dictionary`2&lt;string, string&gt; JsonPathDefinition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.JsonFormat.JsonPathDefinition" />
      <MemberSignature Language="VB.NET" Value="Public Property JsonPathDefinition As Dictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.JsonPathDefinition : System.Collections.Generic.Dictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.JsonFormat.JsonPathDefinition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.Dictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Optional. Die Definition der relativen JSONPath in die ursprünglichen JSON-Objekte für die entsprechenden Spalte in der konvertierten Zeile beim Konvertieren von JSON-Objekten auf Zeilen. Beispiel: {"Column1": "$. Column1Path"}. Die JSONPath der Stamm-Elemente muss mit einem "$"-Zeichens starten. Alle anderen Elemente im vereinfachten von JsonNodeReference definierten Array darf nicht aus.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NestingSeparator">
      <MemberSignature Language="C#" Value="public string NestingSeparator { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NestingSeparator" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.JsonFormat.NestingSeparator" />
      <MemberSignature Language="VB.NET" Value="Public Property NestingSeparator As String" />
      <MemberSignature Language="F#" Value="member this.NestingSeparator : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.JsonFormat.NestingSeparator" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Das Zeichen zum Trennen der Schachtelungsebenen verwendet. Standardwert ist "." (Punkt). 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>