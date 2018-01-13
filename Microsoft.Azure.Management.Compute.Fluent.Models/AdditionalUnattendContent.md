<Type Name="AdditionalUnattendContent" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.AdditionalUnattendContent">
  <TypeSignature Language="C#" Value="public class AdditionalUnattendContent" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AdditionalUnattendContent extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.AdditionalUnattendContent" />
  <TypeSignature Language="VB.NET" Value="Public Class AdditionalUnattendContent" />
  <TypeSignature Language="F#" Value="type AdditionalUnattendContent = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Zusätzliches mit XML formatierten Informationen, die in der Datei "Unattend.xml" aufgenommen werden kann, die von Windows Setup verwendet wird. Inhalte werden definiert, durch Festlegen von Name, Komponentenname und die Übergabe an, in der der Inhalt angewendet wird.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdditionalUnattendContent ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.AdditionalUnattendContent.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der AdditionalUnattendContent-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdditionalUnattendContent (Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.PassNames&gt; passName = null, Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ComponentNames&gt; componentName = null, Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SettingNames&gt; settingName = null, string content = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.PassNames&gt; passName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.ComponentNames&gt; componentName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.SettingNames&gt; settingName, string content) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.AdditionalUnattendContent.#ctor(System.Nullable{Microsoft.Azure.Management.Compute.Fluent.Models.PassNames},System.Nullable{Microsoft.Azure.Management.Compute.Fluent.Models.ComponentNames},System.Nullable{Microsoft.Azure.Management.Compute.Fluent.Models.SettingNames},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional passName As Nullable(Of PassNames) = null, Optional componentName As Nullable(Of ComponentNames) = null, Optional settingName As Nullable(Of SettingNames) = null, Optional content As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.AdditionalUnattendContent : Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.PassNames&gt; * Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ComponentNames&gt; * Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SettingNames&gt; * string -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.AdditionalUnattendContent" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.AdditionalUnattendContent (passName, componentName, settingName, content)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="passName" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.PassNames&gt;" />
        <Parameter Name="componentName" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ComponentNames&gt;" />
        <Parameter Name="settingName" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SettingNames&gt;" />
        <Parameter Name="content" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="passName">Der Name übergeben. Derzeit ist der einzige zulässige Wert "oobeSystem". Folgende Werte sind möglich: "OobeSystem"</param>
        <param name="componentName">Der Komponentenname. Derzeit ist der einzige zulässige Wert Microsoft-Windows-Shell-Setup. Folgende Werte sind möglich: "Microsoft-Windows-Shell-Setup"</param>
        <param name="settingName">Einstellungsname (z. B. FirstLogonCommands, AutoLogon). Folgende Werte sind möglich: "Anmeldung", "FirstLogonCommands"</param>
        <param name="content">Mit XML formatierten Inhalt, der die Datei "Unattend.xml" in der angegebenen bestanden wurden und Komponente hinzugefügt wird. Der XML-Code muss weniger als 4 KB und dabei das Stammelement für die Einstellung oder Funktion, die eingefügt wird.</param>
        <summary>
            Initialisiert eine neue Instanz der AdditionalUnattendContent-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComponentName">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ComponentNames&gt; ComponentName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.ComponentNames&gt; ComponentName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.AdditionalUnattendContent.ComponentName" />
      <MemberSignature Language="VB.NET" Value="Public Property ComponentName As Nullable(Of ComponentNames)" />
      <MemberSignature Language="F#" Value="member this.ComponentName : Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ComponentNames&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.AdditionalUnattendContent.ComponentName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="componentName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ComponentNames&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen der Komponente. Derzeit ist der einzige zulässige Wert Microsoft-Windows-Shell-Setup. Folgende Werte sind möglich: "Microsoft-Windows-Shell-Setup"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Content">
      <MemberSignature Language="C#" Value="public string Content { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Content" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.AdditionalUnattendContent.Content" />
      <MemberSignature Language="VB.NET" Value="Public Property Content As String" />
      <MemberSignature Language="F#" Value="member this.Content : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.AdditionalUnattendContent.Content" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="content")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt diesen fest XML-Format, um die Datei "Unattend.xml" in der angegebenen bestanden wurden und Komponente hinzugefügt wird. Der XML-Code muss weniger als 4 KB und dabei das Stammelement für die Einstellung oder Funktion, die eingefügt wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PassName">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.PassNames&gt; PassName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.PassNames&gt; PassName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.AdditionalUnattendContent.PassName" />
      <MemberSignature Language="VB.NET" Value="Public Property PassName As Nullable(Of PassNames)" />
      <MemberSignature Language="F#" Value="member this.PassName : Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.PassNames&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.AdditionalUnattendContent.PassName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="passName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.PassNames&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen übergeben. Derzeit ist der einzige zulässige Wert "oobeSystem". Folgende Werte sind möglich: "OobeSystem"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SettingName">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SettingNames&gt; SettingName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.SettingNames&gt; SettingName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.AdditionalUnattendContent.SettingName" />
      <MemberSignature Language="VB.NET" Value="Public Property SettingName As Nullable(Of SettingNames)" />
      <MemberSignature Language="F#" Value="member this.SettingName : Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SettingNames&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.AdditionalUnattendContent.SettingName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="settingName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SettingNames&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest (z. B. FirstLogonCommands, AutoLogon) Name der Einstellung.
            Folgende Werte sind möglich: "Anmeldung", "FirstLogonCommands"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>