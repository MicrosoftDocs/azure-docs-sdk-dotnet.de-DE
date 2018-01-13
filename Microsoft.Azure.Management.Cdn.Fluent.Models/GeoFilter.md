<Type Name="GeoFilter" FullName="Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter">
  <TypeSignature Language="C#" Value="public class GeoFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit GeoFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class GeoFilter" />
  <TypeSignature Language="F#" Value="type GeoFilter = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Regeln, die geografische Benutzerzugriff in einem CDN-Endpunkt zu definieren.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GeoFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der GeoFilter-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GeoFilter (string relativePath, Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilterActions action, System.Collections.Generic.IList&lt;string&gt; countryCodes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string relativePath, valuetype Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilterActions action, class System.Collections.Generic.IList`1&lt;string&gt; countryCodes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter.#ctor(System.String,Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilterActions,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (relativePath As String, action As GeoFilterActions, countryCodes As IList(Of String))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter : string * Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilterActions * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter" Usage="new Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter (relativePath, action, countryCodes)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="relativePath" Type="System.String" />
        <Parameter Name="action" Type="Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilterActions" />
        <Parameter Name="countryCodes" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="relativePath">Relativer Pfad für geografische filtern.
            (z. B. "/ Eigene Bilder, ' / mypicture/kitty.jpg", und usw..)</param>
        <param name="action">Aktion für die geografische filtern, d. h. Zugriff zugelassen oder blockiert. Folgende Werte sind möglich: "Sperren", "Zulassen"</param>
        <param name="countryCodes">Zwei Buchstaben Landeskennzahlen Land Benutzerzugriff in ein geografisches definieren zu filtern, z. B. automatische Updates, MX, USA.</param>
        <summary>
            Initialisiert eine neue Instanz der GeoFilter-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Action">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilterActions Action { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilterActions Action" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter.Action" />
      <MemberSignature Language="VB.NET" Value="Public Property Action As GeoFilterActions" />
      <MemberSignature Language="F#" Value="member this.Action : Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilterActions with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter.Action" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="action")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilterActions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest Aktion die geografische filtern, d. h. Zugriff zugelassen oder blockiert.
            Folgende Werte sind möglich: "Sperren", "Zulassen"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CountryCodes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; CountryCodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; CountryCodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter.CountryCodes" />
      <MemberSignature Language="VB.NET" Value="Public Property CountryCodes As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.CountryCodes : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter.CountryCodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="countryCodes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert zwei Buchstaben Landeskennzahlen Land Benutzerzugriff in einem geografischen Filter definieren z. B. AU, MX, USA.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RelativePath">
      <MemberSignature Language="C#" Value="public string RelativePath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RelativePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter.RelativePath" />
      <MemberSignature Language="VB.NET" Value="Public Property RelativePath As String" />
      <MemberSignature Language="F#" Value="member this.RelativePath : string with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter.RelativePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="relativePath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder relativen Pfad für geografische Filter definiert. (z. B. "/ Eigene Bilder, ' / mypicture/kitty.jpg", und usw..)
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="geoFilter.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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