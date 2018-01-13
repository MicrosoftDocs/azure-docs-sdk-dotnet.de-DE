<Type Name="IWithConnectionString&lt;FluentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithConnectionString&lt;FluentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithConnectionString&lt;FluentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithConnectionString`1&lt;FluentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithConnectionString`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithConnectionString(Of FluentT)" />
  <TypeSignature Language="F#" Value="type IWithConnectionString&lt;'FluentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="FluentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="FluentT"><span data-ttu-id="835a1-101">Der Typ der Ressource.</span><span class="sxs-lookup"><span data-stu-id="835a1-101">The type of the resource.</span></span></typeparam>
    <summary>
            <span data-ttu-id="835a1-102">Eine Web-app Definition Phase Verbindungszeichenfolgen festgelegt werden können.</span><span class="sxs-lookup"><span data-stu-id="835a1-102">A web app definition stage allowing connection strings to be set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithConnectionString">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt; WithConnectionString (string name, string value, Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType type);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate`1&lt;!FluentT&gt; WithConnectionString(string name, string value, valuetype Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithConnectionString`1.WithConnectionString(System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithConnectionString (name As String, value As String, type As ConnectionStringType) As IWithCreate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithConnectionString : string * string * Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;'FluentT&gt;" Usage="iWithConnectionString.WithConnectionString (name, value, type)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
        <Parameter Name="type" Type="Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="835a1-103">Name der Verbindungszeichenfolge:</span><span class="sxs-lookup"><span data-stu-id="835a1-103">The name of the connection string.</span></span></param>
        <param name="value"><span data-ttu-id="835a1-104">Der Wert der Verbindungszeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="835a1-104">The connection string value.</span></span></param>
        <param name="type"><span data-ttu-id="835a1-105">Der Verbindungstyp Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="835a1-105">The connection string type.</span></span></param>
        <summary>
            <span data-ttu-id="835a1-106">Die Web-app hinzugefügt eine Verbindungszeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="835a1-106">Adds a connection string to the web app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="835a1-107">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="835a1-107">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithStickyConnectionString">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt; WithStickyConnectionString (string name, string value, Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType type);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate`1&lt;!FluentT&gt; WithStickyConnectionString(string name, string value, valuetype Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithConnectionString`1.WithStickyConnectionString(System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithStickyConnectionString (name As String, value As String, type As ConnectionStringType) As IWithCreate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithStickyConnectionString : string * string * Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;'FluentT&gt;" Usage="iWithConnectionString.WithStickyConnectionString (name, value, type)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
        <Parameter Name="type" Type="Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="835a1-108">Name der Verbindungszeichenfolge:</span><span class="sxs-lookup"><span data-stu-id="835a1-108">The name of the connection string.</span></span></param>
        <param name="value"><span data-ttu-id="835a1-109">Der Wert der Verbindungszeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="835a1-109">The connection string value.</span></span></param>
        <param name="type"><span data-ttu-id="835a1-110">Der Verbindungstyp Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="835a1-110">The connection string type.</span></span></param>
        <summary>
            <span data-ttu-id="835a1-111">Die Web-app hinzugefügt eine Verbindungszeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="835a1-111">Adds a connection string to the web app.</span></span> <span data-ttu-id="835a1-112">Diese Verbindungszeichenfolge wird ebenfalls nach einem slotaustausch Bereitstellung ausgetauscht werden.</span><span class="sxs-lookup"><span data-stu-id="835a1-112">This connection string will be swapped as well after a deployment slot swap.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="835a1-113">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="835a1-113">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>