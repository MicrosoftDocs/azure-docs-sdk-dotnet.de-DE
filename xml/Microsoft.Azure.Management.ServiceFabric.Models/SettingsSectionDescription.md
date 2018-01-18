<Type Name="SettingsSectionDescription" FullName="Microsoft.Azure.Management.ServiceFabric.Models.SettingsSectionDescription">
  <TypeSignature Language="C#" Value="public class SettingsSectionDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SettingsSectionDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceFabric.Models.SettingsSectionDescription" />
  <TypeSignature Language="VB.NET" Value="Public Class SettingsSectionDescription" />
  <TypeSignature Language="F#" Value="type SettingsSectionDescription = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="03ea7-101">ServiceFabric Abschnitt Einstellungen</span><span class="sxs-lookup"><span data-stu-id="03ea7-101">ServiceFabric section settings</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SettingsSectionDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.SettingsSectionDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="03ea7-102">Initialisiert eine neue Instanz der SettingsSectionDescription-Klasse.</span><span class="sxs-lookup"><span data-stu-id="03ea7-102">Initializes a new instance of the SettingsSectionDescription class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SettingsSectionDescription (string name, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.SettingsParameterDescription&gt; parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ServiceFabric.Models.SettingsParameterDescription&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.SettingsSectionDescription.#ctor(System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.ServiceFabric.Models.SettingsParameterDescription})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, parameters As IList(Of SettingsParameterDescription))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceFabric.Models.SettingsSectionDescription : string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.SettingsParameterDescription&gt; -&gt; Microsoft.Azure.Management.ServiceFabric.Models.SettingsSectionDescription" Usage="new Microsoft.Azure.Management.ServiceFabric.Models.SettingsSectionDescription (name, parameters)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.SettingsParameterDescription&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="03ea7-103">Der Name der Abschnitt ""</span><span class="sxs-lookup"><span data-stu-id="03ea7-103">The name of settings section</span></span></param>
        <param name="parameters"><span data-ttu-id="03ea7-104">Sammlung von Einstellungen im Bereich, wird jede Einstellung ein Tupel besteht, Festlegen von Name und Wert</span><span class="sxs-lookup"><span data-stu-id="03ea7-104">Collection of settings in the section, each setting is a tuple consisting of setting name and value</span></span></param>
        <summary>
            <span data-ttu-id="03ea7-105">Initialisiert eine neue Instanz der SettingsSectionDescription-Klasse.</span><span class="sxs-lookup"><span data-stu-id="03ea7-105">Initializes a new instance of the SettingsSectionDescription class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.SettingsSectionDescription.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.SettingsSectionDescription.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="03ea7-106">Ruft ab oder legt den Namen der Abschnitt ""</span><span class="sxs-lookup"><span data-stu-id="03ea7-106">Gets or sets the name of settings section</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.SettingsParameterDescription&gt; Parameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ServiceFabric.Models.SettingsParameterDescription&gt; Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.SettingsSectionDescription.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public Property Parameters As IList(Of SettingsParameterDescription)" />
      <MemberSignature Language="F#" Value="member this.Parameters : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.SettingsParameterDescription&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.SettingsSectionDescription.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="parameters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.SettingsParameterDescription&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="03ea7-107">Ruft ab oder legt die Auflistung der Einstellungen im Abschnitt, wird jede Einstellung ein Tupel besteht, Festlegen von Name und Wert</span><span class="sxs-lookup"><span data-stu-id="03ea7-107">Gets or sets collection of settings in the section, each setting is a tuple consisting of setting name and value</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.SettingsSectionDescription.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="settingsSectionDescription.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="03ea7-108">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="03ea7-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="03ea7-109">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="03ea7-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>