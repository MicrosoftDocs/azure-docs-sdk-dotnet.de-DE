<Type Name="SiteSeal" FullName="Microsoft.Azure.Management.WebSites.Models.SiteSeal">
  <TypeSignature Language="C#" Value="public class SiteSeal" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SiteSeal extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.SiteSeal" />
  <TypeSignature Language="VB.NET" Value="Public Class SiteSeal" />
  <TypeSignature Language="F#" Value="type SiteSeal = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="92a43-101">Standort versiegeln</span><span class="sxs-lookup"><span data-stu-id="92a43-101">Site seal</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SiteSeal ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SiteSeal.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="92a43-102">Initialisiert eine neue Instanz der SiteSeal-Klasse.</span><span class="sxs-lookup"><span data-stu-id="92a43-102">Initializes a new instance of the SiteSeal class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SiteSeal (string html);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string html) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SiteSeal.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (html As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.SiteSeal : string -&gt; Microsoft.Azure.Management.WebSites.Models.SiteSeal" Usage="new Microsoft.Azure.Management.WebSites.Models.SiteSeal html" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="html" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="html"><span data-ttu-id="92a43-103">HTML-Codeausschnitt</span><span class="sxs-lookup"><span data-stu-id="92a43-103">HTML snippet</span></span></param>
        <summary>
            <span data-ttu-id="92a43-104">Initialisiert eine neue Instanz der SiteSeal-Klasse.</span><span class="sxs-lookup"><span data-stu-id="92a43-104">Initializes a new instance of the SiteSeal class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Html">
      <MemberSignature Language="C#" Value="public string Html { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Html" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteSeal.Html" />
      <MemberSignature Language="VB.NET" Value="Public Property Html As String" />
      <MemberSignature Language="F#" Value="member this.Html : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteSeal.Html" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="html")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="92a43-105">Ruft ab oder legt Sie HTML-Codeausschnitt fest.</span><span class="sxs-lookup"><span data-stu-id="92a43-105">Gets or sets HTML snippet</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SiteSeal.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="siteSeal.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="92a43-106">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="92a43-106">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="92a43-107">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="92a43-107">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>