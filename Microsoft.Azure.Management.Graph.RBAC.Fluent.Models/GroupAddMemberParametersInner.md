<Type Name="GroupAddMemberParametersInner" FullName="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupAddMemberParametersInner">
  <TypeSignature Language="C#" Value="public class GroupAddMemberParametersInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit GroupAddMemberParametersInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupAddMemberParametersInner" />
  <TypeSignature Language="VB.NET" Value="Public Class GroupAddMemberParametersInner" />
  <TypeSignature Language="F#" Value="type GroupAddMemberParametersInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="568ea-101">Fordern Sie Parameter für das Hinzufügen eines Mitglieds zu einer Gruppe an.</span><span class="sxs-lookup"><span data-stu-id="568ea-101">Request parameters for adding a member to a group.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GroupAddMemberParametersInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupAddMemberParametersInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="568ea-102">Initialisiert eine neue Instanz der GroupAddMemberParametersInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="568ea-102">Initializes a new instance of the GroupAddMemberParametersInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GroupAddMemberParametersInner (string url);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string url) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupAddMemberParametersInner.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (url As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupAddMemberParametersInner : string -&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupAddMemberParametersInner" Usage="new Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupAddMemberParametersInner url" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="url" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="url"><span data-ttu-id="568ea-103">Eine URL für das Member-Objekt, z. B. "https://graph.windows.net/0b1f9851-1bf0-433f-aec3-cb9272f093dc/directoryObjects/f260bbc4-c254-447b-94cf-293b5ec434dd", wobei "0b1f9851-1bf0-433f-aec3-cb9272f093dc" der "tenantid" ist und " f260bbc4-c254-447b-94cf-293b5ec434dd"ist die ObjectId des Mitglieds (Benutzer, Anwendung, ServicePrincipal, Gruppe), hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="568ea-103">A member object URL, such as "https://graph.windows.net/0b1f9851-1bf0-433f-aec3-cb9272f093dc/directoryObjects/f260bbc4-c254-447b-94cf-293b5ec434dd", where "0b1f9851-1bf0-433f-aec3-cb9272f093dc" is the tenantId and "f260bbc4-c254-447b-94cf-293b5ec434dd" is the objectId of the member (user, application, servicePrincipal, group) to be added.</span></span></param>
        <summary>
            <span data-ttu-id="568ea-104">Initialisiert eine neue Instanz der GroupAddMemberParametersInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="568ea-104">Initializes a new instance of the GroupAddMemberParametersInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupAddMemberParametersInner.Url" />
      <MemberSignature Language="VB.NET" Value="Public Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupAddMemberParametersInner.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="url")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="568ea-105">Ruft ab oder legt ein Element URL des Objekts, z. B. "https://graph.windows.net/0b1f9851-1bf0-433f-aec3-cb9272f093dc/directoryObjects/f260bbc4-c254-447b-94cf-293b5ec434dd", wobei "0b1f9851-1bf0-433f-aec3-cb9272f093dc" der "tenantid" ist und " f260bbc4-c254-447b-94cf-293b5ec434dd"ist die ObjectId des Mitglieds (Benutzer, Anwendung, ServicePrincipal, Gruppe), hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="568ea-105">Gets or sets a member object URL, such as "https://graph.windows.net/0b1f9851-1bf0-433f-aec3-cb9272f093dc/directoryObjects/f260bbc4-c254-447b-94cf-293b5ec434dd", where "0b1f9851-1bf0-433f-aec3-cb9272f093dc" is the tenantId and "f260bbc4-c254-447b-94cf-293b5ec434dd" is the objectId of the member (user, application, servicePrincipal, group) to be added.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupAddMemberParametersInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="groupAddMemberParametersInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="568ea-106">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="568ea-106">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="568ea-107">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="568ea-107">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>