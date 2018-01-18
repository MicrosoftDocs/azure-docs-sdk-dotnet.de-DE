<Type Name="TagScoringParameters" FullName="Microsoft.Azure.Search.Models.TagScoringParameters">
  <TypeSignature Language="C#" Value="public class TagScoringParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TagScoringParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.TagScoringParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class TagScoringParameters" />
  <TypeSignature Language="F#" Value="type TagScoringParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9ddd8-101">Parameterwerte für ein Tag Bewertungsfunktion bereitstellt.</span><span class="sxs-lookup"><span data-stu-id="9ddd8-101">Provides parameter values to a tag scoring function.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TagScoringParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.TagScoringParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9ddd8-102">Initialisiert eine neue Instanz der TagScoringParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9ddd8-102">Initializes a new instance of the TagScoringParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TagScoringParameters (string tagsParameter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string tagsParameter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.TagScoringParameters.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (tagsParameter As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.TagScoringParameters : string -&gt; Microsoft.Azure.Search.Models.TagScoringParameters" Usage="new Microsoft.Azure.Search.Models.TagScoringParameters tagsParameter" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tagsParameter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tagsParameter"><span data-ttu-id="9ddd8-103">Der Name des Parameters übergeben in Suchabfragen an die Liste der Tags, die mit dem Feld "Ziel" verglichen.</span><span class="sxs-lookup"><span data-stu-id="9ddd8-103">The name of the parameter passed in search queries to specify the list of tags to compare against the target field.</span></span></param>
        <summary>
            <span data-ttu-id="9ddd8-104">Initialisiert eine neue Instanz der TagScoringParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9ddd8-104">Initializes a new instance of the TagScoringParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TagsParameter">
      <MemberSignature Language="C#" Value="public string TagsParameter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TagsParameter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.TagScoringParameters.TagsParameter" />
      <MemberSignature Language="VB.NET" Value="Public Property TagsParameter As String" />
      <MemberSignature Language="F#" Value="member this.TagsParameter : string with get, set" Usage="Microsoft.Azure.Search.Models.TagScoringParameters.TagsParameter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tagsParameter")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9ddd8-105">Ruft ab oder legt den Namen des Parameters in Suchabfragen an die Liste der Tags zum Vergleich von Feld "Ziel" übergeben.</span><span class="sxs-lookup"><span data-stu-id="9ddd8-105">Gets or sets the name of the parameter passed in search queries to specify the list of tags to compare against the target field.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.TagScoringParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="tagScoringParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9ddd8-106">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="9ddd8-106">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9ddd8-107">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="9ddd8-107">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>