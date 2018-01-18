<Type Name="IWithConnectionString&lt;FluentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithConnectionString&lt;FluentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithConnectionString&lt;FluentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithConnectionString`1&lt;FluentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithConnectionString`1" />
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
    <typeparam name="FluentT"><span data-ttu-id="8b7fc-101">Der Typ der Ressource.</span><span class="sxs-lookup"><span data-stu-id="8b7fc-101">The type of the resource.</span></span></typeparam>
    <summary>
            <span data-ttu-id="8b7fc-102">Eine Web-app aktualisieren Stufe ermöglicht Verbindungszeichenfolgen festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="8b7fc-102">A web app update stage allowing connection strings to be set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithConnectionString">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithConnectionString (string name, string value, Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType type);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithConnectionString(string name, string value, valuetype Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithConnectionString`1.WithConnectionString(System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithConnectionString (name As String, value As String, type As ConnectionStringType) As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithConnectionString : string * string * Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithConnectionString.WithConnectionString (name, value, type)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
        <Parameter Name="type" Type="Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="8b7fc-103">Name der Verbindungszeichenfolge:</span><span class="sxs-lookup"><span data-stu-id="8b7fc-103">The name of the connection string.</span></span></param>
        <param name="value"><span data-ttu-id="8b7fc-104">Der Wert der Verbindungszeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="8b7fc-104">The connection string value.</span></span></param>
        <param name="type"><span data-ttu-id="8b7fc-105">Der Verbindungstyp Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="8b7fc-105">The connection string type.</span></span></param>
        <summary>
            <span data-ttu-id="8b7fc-106">Die Web-app hinzugefügt eine Verbindungszeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="8b7fc-106">Adds a connection string to the web app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="8b7fc-107">Die nächste Phase des Web-app-Updates.</span><span class="sxs-lookup"><span data-stu-id="8b7fc-107">The next stage of the web app update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithConnectionStringStickiness">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithConnectionStringStickiness (string name, bool sticky);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithConnectionStringStickiness(string name, bool sticky) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithConnectionString`1.WithConnectionStringStickiness(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithConnectionStringStickiness (name As String, sticky As Boolean) As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithConnectionStringStickiness : string * bool -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithConnectionString.WithConnectionStringStickiness (name, sticky)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="sticky" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="8b7fc-108">Name der Verbindungszeichenfolge:</span><span class="sxs-lookup"><span data-stu-id="8b7fc-108">The name of the connection string.</span></span></param>
        <param name="sticky"><span data-ttu-id="8b7fc-109">"True", wenn die Verbindungszeichenfolge in das Einschubfach während einen Austausch sticks.</span><span class="sxs-lookup"><span data-stu-id="8b7fc-109">True if the connection string sticks to the slot during a swap.</span></span></param>
        <summary>
            <span data-ttu-id="8b7fc-110">Ändert die Klebrigkeit eine Verbindungszeichenfolge an.</span><span class="sxs-lookup"><span data-stu-id="8b7fc-110">Changes the stickiness of a connection string.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="8b7fc-111">Die nächste Phase des Web-app-Updates.</span><span class="sxs-lookup"><span data-stu-id="8b7fc-111">The next stage of the web app update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutConnectionString">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithoutConnectionString (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithoutConnectionString(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithConnectionString`1.WithoutConnectionString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutConnectionString (name As String) As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithoutConnectionString : string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithConnectionString.WithoutConnectionString name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="8b7fc-112">Name der Verbindungszeichenfolge:</span><span class="sxs-lookup"><span data-stu-id="8b7fc-112">The name of the connection string.</span></span></param>
        <summary>
            <span data-ttu-id="8b7fc-113">Entfernt eine Verbindungszeichenfolge aus der Web-app.</span><span class="sxs-lookup"><span data-stu-id="8b7fc-113">Removes a connection string from the web app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="8b7fc-114">Die nächste Phase des Web-app-Updates.</span><span class="sxs-lookup"><span data-stu-id="8b7fc-114">The next stage of the web app update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithStickyConnectionString">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithStickyConnectionString (string name, string value, Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType type);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithStickyConnectionString(string name, string value, valuetype Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithConnectionString`1.WithStickyConnectionString(System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithStickyConnectionString (name As String, value As String, type As ConnectionStringType) As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithStickyConnectionString : string * string * Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithConnectionString.WithStickyConnectionString (name, value, type)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
        <Parameter Name="type" Type="Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="8b7fc-115">Name der Verbindungszeichenfolge:</span><span class="sxs-lookup"><span data-stu-id="8b7fc-115">The name of the connection string.</span></span></param>
        <param name="value"><span data-ttu-id="8b7fc-116">Der Wert der Verbindungszeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="8b7fc-116">The connection string value.</span></span></param>
        <param name="type"><span data-ttu-id="8b7fc-117">Der Verbindungstyp Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="8b7fc-117">The connection string type.</span></span></param>
        <summary>
            <span data-ttu-id="8b7fc-118">Die Web-app hinzugefügt eine Verbindungszeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="8b7fc-118">Adds a connection string to the web app.</span></span> <span data-ttu-id="8b7fc-119">Diese Verbindungszeichenfolge, die bei einem Austausch an den Slot verbleibt.</span><span class="sxs-lookup"><span data-stu-id="8b7fc-119">This connection string will stay at the slot during a swap.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="8b7fc-120">Die nächste Phase des Web-app-Updates.</span><span class="sxs-lookup"><span data-stu-id="8b7fc-120">The next stage of the web app update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>