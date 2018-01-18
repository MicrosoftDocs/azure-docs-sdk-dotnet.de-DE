<Type Name="SharedKeys" FullName="Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys">
  <TypeSignature Language="C#" Value="public class SharedKeys" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SharedKeys extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys" />
  <TypeSignature Language="VB.NET" Value="Public Class SharedKeys" />
  <TypeSignature Language="F#" Value="type SharedKeys = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9c743-101">Der gemeinsam verwendeten Schlüssel für einen Arbeitsbereich angezeigt.</span><span class="sxs-lookup"><span data-stu-id="9c743-101">The shared keys for a workspace.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedKeys ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9c743-102">Initialisiert eine neue Instanz der SharedKeys-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9c743-102">Initializes a new instance of the SharedKeys class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedKeys (string primarySharedKey = null, string secondarySharedKey = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string primarySharedKey, string secondarySharedKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional primarySharedKey As String = null, Optional secondarySharedKey As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys : string * string -&gt; Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys" Usage="new Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys (primarySharedKey, secondarySharedKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="primarySharedKey" Type="System.String" />
        <Parameter Name="secondarySharedKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="primarySharedKey"><span data-ttu-id="9c743-103">Der primäre gemeinsam verwendeten Schlüssel einen Arbeitsbereich.</span><span class="sxs-lookup"><span data-stu-id="9c743-103">The primary shared key of a workspace.</span></span></param>
        <param name="secondarySharedKey"><span data-ttu-id="9c743-104">Der sekundäre gemeinsam verwendeten Schlüssel einen Arbeitsbereich.</span><span class="sxs-lookup"><span data-stu-id="9c743-104">The secondary shared key of a workspace.</span></span></param>
        <summary>
            <span data-ttu-id="9c743-105">Initialisiert eine neue Instanz der SharedKeys-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9c743-105">Initializes a new instance of the SharedKeys class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimarySharedKey">
      <MemberSignature Language="C#" Value="public string PrimarySharedKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrimarySharedKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys.PrimarySharedKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PrimarySharedKey As String" />
      <MemberSignature Language="F#" Value="member this.PrimarySharedKey : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys.PrimarySharedKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="primarySharedKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9c743-106">Ruft ab, oder legt ihn fest den freigegebenen Primärschlüssel eines Arbeitsbereichs.</span><span class="sxs-lookup"><span data-stu-id="9c743-106">Gets or sets the primary shared key of a workspace.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondarySharedKey">
      <MemberSignature Language="C#" Value="public string SecondarySharedKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecondarySharedKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys.SecondarySharedKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SecondarySharedKey As String" />
      <MemberSignature Language="F#" Value="member this.SecondarySharedKey : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys.SecondarySharedKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="secondarySharedKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9c743-107">Ruft ab, oder legt ihn fest den sekundären gemeinsam verwendeten Schlüssel einen Arbeitsbereich aus.</span><span class="sxs-lookup"><span data-stu-id="9c743-107">Gets or sets the secondary shared key of a workspace.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>