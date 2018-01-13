<Type Name="RedirectIncompatibleRowSettings" FullName="Microsoft.Azure.Management.DataFactory.Models.RedirectIncompatibleRowSettings">
  <TypeSignature Language="C#" Value="public class RedirectIncompatibleRowSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RedirectIncompatibleRowSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.RedirectIncompatibleRowSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class RedirectIncompatibleRowSettings" />
  <TypeSignature Language="F#" Value="type RedirectIncompatibleRowSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Umleiten der Zeile nicht kompatible Einstellungen
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RedirectIncompatibleRowSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.RedirectIncompatibleRowSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der RedirectIncompatibleRowSettings-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RedirectIncompatibleRowSettings (object linkedServiceName, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, object path = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object linkedServiceName, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, object path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.RedirectIncompatibleRowSettings.#ctor(System.Object,System.Collections.Generic.IDictionary{System.String,System.Object},System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (linkedServiceName As Object, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional path As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.RedirectIncompatibleRowSettings : obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.RedirectIncompatibleRowSettings" Usage="new Microsoft.Azure.Management.DataFactory.Models.RedirectIncompatibleRowSettings (linkedServiceName, additionalProperties, path)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="linkedServiceName" Type="System.Object" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="path" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="linkedServiceName">Name des Azure-Speicher, SAS-Speicher oder Azure Data Lake-Speicher verknüpften Dienst zum Umleiten der Zeile nicht kompatibel. Muss angegeben werden, wenn RedirectIncompatibleRowSettings angegeben wird. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</param>
        <param name="additionalProperties">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</param>
        <param name="path">Der Pfad zum Speichern von Daten aus der inkompatible Zeile umleiten. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</param>
        <summary>
            Initialisiert eine neue Instanz der RedirectIncompatibleRowSettings-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdditionalProperties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; AdditionalProperties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; AdditionalProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.RedirectIncompatibleRowSettings.AdditionalProperties" />
      <MemberSignature Language="VB.NET" Value="Public Property AdditionalProperties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.AdditionalProperties : System.Collections.Generic.IDictionary&lt;string, obj&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.RedirectIncompatibleRowSettings.AdditionalProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonExtensionData</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest, die nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert diese Sammlung
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LinkedServiceName">
      <MemberSignature Language="C#" Value="public object LinkedServiceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object LinkedServiceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.RedirectIncompatibleRowSettings.LinkedServiceName" />
      <MemberSignature Language="VB.NET" Value="Public Property LinkedServiceName As Object" />
      <MemberSignature Language="F#" Value="member this.LinkedServiceName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.RedirectIncompatibleRowSettings.LinkedServiceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="linkedServiceName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Name des Azure-Speicher, SAS-Speicher oder Azure Data Lake-Speicher verknüpften Dienst zum Umleiten der Zeile nicht kompatibel.
            Muss angegeben werden, wenn RedirectIncompatibleRowSettings angegeben wird.
            Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public object Path { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.RedirectIncompatibleRowSettings.Path" />
      <MemberSignature Language="VB.NET" Value="Public Property Path As Object" />
      <MemberSignature Language="F#" Value="member this.Path : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.RedirectIncompatibleRowSettings.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="path")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Pfad zum Speichern von Daten aus der inkompatible Zeile umleiten. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.RedirectIncompatibleRowSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="redirectIncompatibleRowSettings.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
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