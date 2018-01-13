<Type Name="SiteCloneabilityInner" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.SiteCloneabilityInner">
  <TypeSignature Language="C#" Value="public class SiteCloneabilityInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SiteCloneabilityInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.SiteCloneabilityInner" />
  <TypeSignature Language="VB.NET" Value="Public Class SiteCloneabilityInner" />
  <TypeSignature Language="F#" Value="type SiteCloneabilityInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt dar, und zwar unabhängig davon, ob eine app Klonbare ist.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SiteCloneabilityInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.SiteCloneabilityInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der SiteCloneabilityInner-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SiteCloneabilityInner (Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CloneAbilityResult&gt; result = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteCloneabilityCriterion&gt; blockingFeatures = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteCloneabilityCriterion&gt; unsupportedFeatures = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteCloneabilityCriterion&gt; blockingCharacteristics = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.CloneAbilityResult&gt; result, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteCloneabilityCriterion&gt; blockingFeatures, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteCloneabilityCriterion&gt; unsupportedFeatures, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteCloneabilityCriterion&gt; blockingCharacteristics) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.SiteCloneabilityInner.#ctor(System.Nullable{Microsoft.Azure.Management.AppService.Fluent.Models.CloneAbilityResult},System.Collections.Generic.IList{Microsoft.Azure.Management.AppService.Fluent.Models.SiteCloneabilityCriterion},System.Collections.Generic.IList{Microsoft.Azure.Management.AppService.Fluent.Models.SiteCloneabilityCriterion},System.Collections.Generic.IList{Microsoft.Azure.Management.AppService.Fluent.Models.SiteCloneabilityCriterion})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional result As Nullable(Of CloneAbilityResult) = null, Optional blockingFeatures As IList(Of SiteCloneabilityCriterion) = null, Optional unsupportedFeatures As IList(Of SiteCloneabilityCriterion) = null, Optional blockingCharacteristics As IList(Of SiteCloneabilityCriterion) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.SiteCloneabilityInner : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CloneAbilityResult&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteCloneabilityCriterion&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteCloneabilityCriterion&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteCloneabilityCriterion&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.SiteCloneabilityInner" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.SiteCloneabilityInner (result, blockingFeatures, unsupportedFeatures, blockingCharacteristics)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="result" Type="System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CloneAbilityResult&gt;" />
        <Parameter Name="blockingFeatures" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteCloneabilityCriterion&gt;" />
        <Parameter Name="unsupportedFeatures" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteCloneabilityCriterion&gt;" />
        <Parameter Name="blockingCharacteristics" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteCloneabilityCriterion&gt;" />
      </Parameters>
      <Docs>
        <param name="result">Name der app. Folgende Werte sind möglich: "Klonbare", "PartiallyCloneable", "NotCloneable"</param>
        <param name="blockingFeatures">Liste der App aktivierten Funktionen, die Klonen zu verhindern.</param>
        <param name="unsupportedFeatures">Liste der App aktivierten Funktionen, die nicht blockierend kann nicht geklont werden. Die app noch geklont werden kann, aber die Funktionen in dieser Liste werden nicht eingerichtet werden geklonte app.</param>
        <param name="blockingCharacteristics">Liste der Anwendungsmerkmale blockiert.</param>
        <summary>
            Initialisiert eine neue Instanz der SiteCloneabilityInner-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlockingCharacteristics">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteCloneabilityCriterion&gt; BlockingCharacteristics { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteCloneabilityCriterion&gt; BlockingCharacteristics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteCloneabilityInner.BlockingCharacteristics" />
      <MemberSignature Language="VB.NET" Value="Public Property BlockingCharacteristics As IList(Of SiteCloneabilityCriterion)" />
      <MemberSignature Language="F#" Value="member this.BlockingCharacteristics : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteCloneabilityCriterion&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteCloneabilityInner.BlockingCharacteristics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="blockingCharacteristics")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteCloneabilityCriterion&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der Anwendungsmerkmale blockiert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlockingFeatures">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteCloneabilityCriterion&gt; BlockingFeatures { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteCloneabilityCriterion&gt; BlockingFeatures" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteCloneabilityInner.BlockingFeatures" />
      <MemberSignature Language="VB.NET" Value="Public Property BlockingFeatures As IList(Of SiteCloneabilityCriterion)" />
      <MemberSignature Language="F#" Value="member this.BlockingFeatures : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteCloneabilityCriterion&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteCloneabilityInner.BlockingFeatures" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="blockingFeatures")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteCloneabilityCriterion&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der App aktivierten Funktionen, die Klonen zu verhindern.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Result">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CloneAbilityResult&gt; Result { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.CloneAbilityResult&gt; Result" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteCloneabilityInner.Result" />
      <MemberSignature Language="VB.NET" Value="Public Property Result As Nullable(Of CloneAbilityResult)" />
      <MemberSignature Language="F#" Value="member this.Result : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CloneAbilityResult&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteCloneabilityInner.Result" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="result")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CloneAbilityResult&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen der app fest. Folgende Werte sind möglich: "Klonbare", "PartiallyCloneable", "NotCloneable"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnsupportedFeatures">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteCloneabilityCriterion&gt; UnsupportedFeatures { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteCloneabilityCriterion&gt; UnsupportedFeatures" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteCloneabilityInner.UnsupportedFeatures" />
      <MemberSignature Language="VB.NET" Value="Public Property UnsupportedFeatures As IList(Of SiteCloneabilityCriterion)" />
      <MemberSignature Language="F#" Value="member this.UnsupportedFeatures : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteCloneabilityCriterion&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteCloneabilityInner.UnsupportedFeatures" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="unsupportedFeatures")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteCloneabilityCriterion&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der App aktivierten Funktionen, die nicht blockierend kann nicht geklont werden. Die app noch geklont werden kann, aber die Funktionen in dieser Liste werden nicht eingerichtet werden geklonte app.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>